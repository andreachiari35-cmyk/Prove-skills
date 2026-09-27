# Studio M.B. Srl — San Paolo (BS)

Sito dello Studio M.B. Srl (amministratore unico: Mario Monteverdi, Ragioniere).
Statico: `index.html` + `tokens.css` + `styles.css`, nessun build.

Artifact pubblicato: https://claude.ai/artifact/RwfSNP1vfvHfEgi8UC46nc

## Impianto

| Parte | Scelta |
| --- | --- |
| Nav | N3 rail laterale (diventa barra in alto sotto i 68rem) |
| Apertura | Diptych testo/foto, foto al vivo sul bordo destro |
| Servizi | F3 prospetto tabellare, cinque aree numerate |
| Chi siamo | Diptych invertito, ritratto reale |
| Lo studio | Galleria a campiture disuguali |
| Contatti | Diptych dati / mappa + esterno |
| Footer | Ft2 riga unica |
| Tema | custom: bordeaux (hue 18), bianchi caldi, legno chiaro |
| Tipografia | Newsreader (titoli) · IBM Plex Sans (testo) · Big Shoulders Display (solo logo) |

Tutti i colori e i font passano da `tokens.css`: `styles.css` non contiene
valori cromatici o tipografici inline.

## Da completare

- **Dati dello studio**: `[INDIRIZZO]`, `[TELEFONO]`, `[EMAIL]`, `[ORARI]`, `[P.IVA]`
- **Foto**: 8 riquadri su 9 sono ancora brief per il fotografo. Solo
  `foto/ritratto-titolare.jpg` è reale.
- **Logo**: il wordmark in `.rail__brand` e nel footer è testo provvisorio.
- **Mappa**: segnaposto in `.contact__media`.
- **Link**: i bottoni "Chiama" e "Prenota un appuntamento" puntano a `href="#"`.
- **Pagine legali**: Privacy e Cookie nel footer puntano a `href="#"`.
