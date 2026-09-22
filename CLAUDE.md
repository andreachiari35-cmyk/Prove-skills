# Istruzioni per Claude

## Web development: prima l'intervista

Ogni volta che il lavoro riguarda web development (una pagina, un sito, una web
app, un componente, una modifica di layout o di comportamento), usa la skill
`brainstorming` **prima** di scrivere codice, anche se la richiesta sembra
semplice:

1. Intervistami **una domanda alla volta**, a scelta multipla quando possibile:
   scopo, pubblico, contenuti, vincoli (stack, hosting, dispositivi), criteri di
   successo.
2. Riscrivi quello che hai capito, separando quello che ho detto dalle tue
   ipotesi, e aspetta la mia correzione.
3. Proponi 2-3 approcci con il tuo consiglio, poi il design, e aspetta la mia
   approvazione esplicita prima di implementare.

Rispondi e fai le domande in italiano.

## Rapporto con gli strumenti di design

Per la parte visiva ci sono tre strumenti a disposizione. Vengono tutti
**dopo** l'intervista, e **nessuno è obbligatorio**: scegli solo quelli che
servono al lavoro, anche uno solo o nessuno.

| Strumento | Tipo | Quando serve |
| --- | --- | --- |
| `hallmark` | skill (in questo repo) | Pagine o siti nuovi e redesign: macrostruttura, tema, tipografia. |
| `impeccable` | skill (in questo repo) | Qualità e rifinitura di un'interfaccia: audit, critique, polish, accessibilità, responsive, animazioni. |
| Originkit | connettore MCP (`mcp__Originkit__*`) | Componenti pronti (hero, navbar, pricing, card, form, animazioni) per React, Next.js, Vite o Framer. |

Esempi di scelta:

- Landing page nuova in HTML/CSS: `hallmark`, gli altri solo se servono.
- Sito in React o Next.js che ha bisogno di una navbar o di un pricing:
  Originkit per quei componenti.
- Pagina esistente da sistemare o controllare: `impeccable`.
- Piccola modifica di comportamento senza impatto visivo: nessuno dei tre.

Regole:

- Le risposte dell'intervista (pubblico, uso, tono, stack) valgono come brief
  per gli strumenti scelti, quindi non ripetere le loro domande se ho già
  risposto.
- Nel design che mi presenti per l'approvazione dì quali strumenti usi e
  perché, in una riga. Posso aggiungerne o toglierne uno.
- Non usare `hallmark` e `impeccable` per decidere la stessa cosa (per esempio
  il tema): se li usi entrambi, `hallmark` imposta la direzione e `impeccable`
  la controlla e la rifinisce.
- Dopo l'approvazione, implementa con gli strumenti scelti. Questa istruzione
  prevale sulla regola di `brainstorming` che vieta di invocare skill diverse
  da `writing-plans`.
- Se uno strumento scelto non è disponibile nella sessione, dillo e prosegui
  con gli altri.

Salta l'intervista solo se te lo chiedo esplicitamente ("vai", "niente
domande", "fai tu").
