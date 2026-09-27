# Studio M.B. Srl — San Paolo (BS)

Sito dello Studio M.B. Srl (amministratore unico: Mario Monteverdi, tributarista).
Statico: `index.html` + `tokens.css` + `styles.css`, nessun build.

Artifact pubblicato: https://claude.ai/artifact/RwfSNP1vfvHfEgi8UC46nc

## Impianto

| Parte | Scelta |
| --- | --- |
| Nav | N3 rail laterale (diventa barra in alto sotto i 68rem) |
| Apertura | Diptych testo/foto, foto al vivo sul bordo destro |
| Servizi | F3 prospetto tabellare: dodici servizi numerati in quattro ambiti (impresa, lavoro e paghe, privati e famiglia, adempimenti e certificazioni) |
| Chi siamo | Diptych invertito, ritratto reale |
| Lo studio | Galleria a campiture disuguali |
| Contatti | Diptych dati / mappa + esterno |
| Footer | Ft2 riga unica |
| Tema | custom: bordeaux (hue 18), bianchi caldi, legno chiaro |
| Tipografia | Newsreader (titoli) · IBM Plex Sans (testo) · Big Shoulders Display (solo logo) |

Tutti i colori e i font passano da `tokens.css`: `styles.css` non contiene
valori cromatici o tipografici inline.

## Da completare

- **Prenota un appuntamento**: i due bottoni puntano ancora a `href="#"`. Serve
  un canale (modulo o servizio di prenotazione). I bottoni "Chiama" chiamano lo
  030 997 0261 da telefono e mostrano il numero da computer.
- **Foto**: 8 riquadri su 9 sono ancora brief per il fotografo. Solo
  `foto/ritratto-titolare.jpg` è reale.
- **Logo**: il wordmark in `.rail__brand` e nel footer è testo provvisorio.
- **Pagine legali**: Privacy e Cookie nel footer puntano a `href="#"`.
- **TASI**: il servizio 08 si chiama "IMU e TASI" come nel documento dello
  studio, ma la TASI è stata abolita nel 2020 (assorbita nell'IMU). Da
  confermare con il cliente.
