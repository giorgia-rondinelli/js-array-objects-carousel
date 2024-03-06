Carosello Array di Oggetti
===
Dato un array di oggetti letterali con:
 - url dell’immagine
 - titolo
 - descrizione
Creare un carosello
## Svolgimento 
- inserisco le immagini con un template litaral 
- inserisco un contatore 
- raggruppo tutti gli elementi con classe 'my-carousel-item'
- rendo visibile solo la prima immagine con la classe active 
- aggiungo i bottoni e faccio si che al loro click il counter aumenti e venga di conseguanza tolta e reinserita la classe active 
- creo una const prendendo il contenitore delle thumbnails
- stampo le thumbnails in pagina con il template literal 
- le raccruppo in una variabile 
- utilizzando il counter anche per quest'ultime faccio si che al clic dei bottoni il counter aumenti e di conseguenza venga tolta e reinserita la classe active 
- aggiungo un setinterval per creare uno scorrimento automantico 
-  in quest'ultimo faccio aumentare il counter e di conseguanza tolgo e reinserisco la classe active
