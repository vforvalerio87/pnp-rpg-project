#Sistema gioco di ruolo
*di Valerio Versace*

Per visualizzare il documento è sufficiente aprire il file **index.html** con qualsiasi browser.

Per modificare il documento è sufficiente modificare il file **content.md**.

Il documento index.html, attraverso uno script, ricarica dinamicamente il contenuto del file content.md e lo inietta all'interno dell'elemento `<div id="content">` a intervalli di 1 secondo.

È possibile caricare il contenuto del documento renderizzato, privo dei tag `<script>`, all'interno di un bucket S3.
A questo proposito, il documento espone delle funzioni che possono essere chiamate direttamente dalla console del browser. Queste funzioni sono:

```javascript
configure(accessKeyId, secretAccessKey, bucket, region)
```
Consente di impostare l'ambiente di lavoro configurando le credenziali di IAM di AWS, il nome del bucket all'interno del quale caricare il documento e la region in cui questo bucket risiede. Tutti i parametri sono *stringhe*.

```javascript
deploy()
```
Carica il documento col nome di **index.html** con accesso pubblico in lettura e `ContentType="text/html; charset=UTF-8"` alla radice del bucket specificato con la funzione `configure(accessKeyId, secretAccessKey, bucket, region)`; vengono rimossi dal documento caricato i tag con `class="dev"`.

Per caricare il documento è necessario che l'utente le cui credenziali vengono specificate in `configure(accessKeyId, secretAccessKey, bucket, region)` abbia i permessi per l'action `s3:PutObject` sul bucket di destinazione e che sul bucket sia correttamente configurato il CORS.
