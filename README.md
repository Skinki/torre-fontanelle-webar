# Torre Fontanelle · WebAR GPS

Pagina statica per la prova WebAR GPS della Torre Fontanelle. Non richiede un’app: il visitatore apre il sito in Safari o Chrome, autorizza fotocamera, posizione e movimento, e il browser colloca il modello alle coordinate impostate nel prototipo.

## Pubblicazione prevista

Per GitHub Pages gratuito, il repository dovrà essere pubblico. Pubblicare questa cartella renderà quindi pubblici la pagina e il GLB, che sarà scaricabile da chiunque. Il modello 3D è incluso per la visualizzazione del prototipo; il repository non concede una licenza di riuso dell’asset.

Caricare il contenuto di questa cartella nella radice del repository e attivare GitHub Pages dalla branch `main`, cartella `/ (root)`. Il link del sito avrà la forma `https://<utente>.github.io/<repository>/`.

## Note per la prova

- Il modello è ottimizzato con Draco e texture WebP (circa 3,7 MB); la pagina usa un decoder Draco ospitato dal CDN Google.
- La posizione è una stima GPS/bussola, non un ancoraggio VPS: precisione e orientamento variano in base al dispositivo e al luogo.
- La pagina chiede accesso a fotocamera, posizione e sensori del dispositivo.
- Il sito deve essere servito via HTTPS.
