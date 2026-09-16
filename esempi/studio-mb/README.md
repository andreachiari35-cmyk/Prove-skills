# Studio M.B. Srl — bozza del sito

Bozza statica di una pagina sola con sezioni ancorate, in italiano, costruita con
la skill `hallmark`. Serve a due cose: mostrare il design al cliente e dare al
fotografo l’elenco degli scatti da fare.

**Non è un sito funzionante.** Tutti i pulsanti sono `href="#"`, non c'è
JavaScript, non c'è un backend, il modulo di prenotazione non esiste ancora.

## File

| File | Cosa contiene |
| --- | --- |
| `index.html` | La pagina: header, apertura, aree di competenza, chi siamo, lo studio, contatti, footer. |
| `tokens.css` | Colori, tipografia, spaziature, tempi. Ogni valore della pagina passa da qui. |
| `styles.css` | Il layout. Nessun colore e nessun font scritti a mano: solo `var(--…)`. |

Si apre facendo doppio clic su `index.html`: non serve installare niente. I font
(Newsreader, IBM Plex Sans, Big Shoulders Display) arrivano da Google Fonts, quindi
per vederli come previsto serve la connessione; senza rete la pagina resta leggibile
con i font di sistema. Prima di andare online conviene scaricarli e servirli dal
dominio dello studio, così il sito non dipende da un terzo.

## Scelte di design

- **Struttura**: dittici che si alternano (testo a sinistra / immagine a destra e
  viceversa), non il solito schema apertura → tre riquadri → pulsante.
- **Colore**: bordeaux `oklch(41% 0.125 18)` come accento — pulsante principale,
  numeri delle aree, filo del menu laterale, una fascia sola nei contatti. Il
  resto è bianco caldo, grigi chiari e un grigio-legno per la sezione «Chi siamo».
- **Tipografia**: Newsreader (serif) per i titoli, IBM Plex Sans per testo ed
  etichette, Big Shoulders Display solo per il logo segnaposto.
- **Menu**: colonna fissa a sinistra sopra i 1088 px, barra in alto sotto.
- **Logo**: «MB» con «STUDIO» in verticale è un **segnaposto di testo**. Va
  sostituito con il file originale quando arriva.

## Cosa manca e va confermato dal cliente

I dati non forniti sono segnaposto in maiuscolo dentro parentesi quadre, così si
vedono a colpo d’occhio: `[INDIRIZZO]`, `[TELEFONO]`, `[EMAIL]`, `[ORARI]`,
`[P.IVA]`. Vanno riempiti prima di pubblicare.

Anche le **descrizioni delle cinque aree di competenza** sono una proposta scritta
a partire dai soli nomi delle aree: vanno lette e corrette dallo studio prima di
andare online. Nel sito non compaiono numeri, anni, statistiche, recensioni o
testimonianze: non c’era niente di verificato da mettere.

La mappa è un riquadro segnaposto: al suo posto andrà la mappa vera o un’immagine
statica con il link alle indicazioni stradali.

---

# Elenco degli scatti per il fotografo

Nove scatti. Nella pagina ogni riquadro grigio riporta già, scritto dentro, cosa
deve contenere e in che proporzioni. Da evitare ovunque: strette di mano,
calcolatrici in primo piano, grafici finti, sorrisi da foto stock.

| # | Sezione | Orientamento | Proporzioni | Cosa inquadrare |
| --- | --- | --- | --- | --- |
| 1 | Apertura | Orizzontale | 16 : 9 | Reception: bancone curvo con piano in vetro, luce naturale, ambiente ordinato. È la prima immagine del sito: nessun cavo, nessuna carta in vista. |
| 2 | Aree di competenza | Verticale | 3 : 4 | Targa bordeaux con i servizi in scritte bianche. Frontale, ritaglio stretto sul testo. |
| 3 | Chi siamo | Verticale | 4 : 5 | Ritratto di Mario Monteverdi in studio: luce morbida, espressione aperta, logo sfocato sullo sfondo. Mezzobusto. |
| 4 | Lo studio | Orizzontale | 3 : 2 | Logo MB sulla porta a vetri, ripreso frontalmente, con l’ambiente dietro leggermente fuori fuoco. |
| 5 | Lo studio | Orizzontale | 3 : 2 | Ufficio operativo: postazione di lavoro con parquet e parete bianca, inquadratura pulita. |
| 6 | Lo studio | Orizzontale | 3 : 2 | Sala riunioni: tavolo vuoto e in ordine, quadro astratto rosso nell’inquadratura, luce naturale laterale. |
| 7 | Lo studio | Orizzontale | 3 : 2 | Secondo ufficio o scorcio del corridoio: parquet, pareti bianche, profondità di campo. |
| 8 | Lo studio | Orizzontale | 3 : 2 | Lavoro in corso: mani su documenti o tastiera, oppure colleghi al lavoro — solo con il loro consenso. |
| 9 | Contatti | Orizzontale | 3 : 2 | Esterno: ingresso o edificio, per far riconoscere il posto a chi arriva la prima volta. |

**Consegna consigliata**: JPEG con il lato lungo di almeno 2400 px, senza filtri e
senza cornici. Gli scatti orizzontali servono a circa 2400 × 1600 px (3 : 2) e
2400 × 1350 px (16 : 9); i verticali a 1200 × 1600 px (3 : 4) e 1600 × 2000 px (4 : 5).
Se uno scatto ritrae persone riconoscibili serve la loro liberatoria.
