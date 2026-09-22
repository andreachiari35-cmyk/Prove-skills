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

Per la parte visiva ho tre strumenti, e tutti vengono **dopo** l'intervista:

| Strumento | Tipo | Quando usarlo |
| --- | --- | --- |
| `hallmark` | skill (in questo repo) | Direzione visiva di pagine nuove o redesign: macrostruttura, tema, tipografia. |
| `impeccable` | skill | Qualità del design e rifinitura: regole di stile e revisione dell'interfaccia. |
| Originkit | connettore MCP (`mcp__Originkit__*`) | Componenti pronti (hero, navbar, pricing, card, form, animazioni) per React, Next.js, Vite o Framer. |

- Le risposte dell'intervista (pubblico, uso, tono, stack) valgono come brief
  per tutti e tre, quindi non ripetere le loro domande se ho già risposto.
- Nel design che mi presenti per l'approvazione indica quale strumento usi per
  ogni parte: tema e struttura da `hallmark`, componenti da Originkit (cercali
  con `search` e cita quali), controlli di qualità da `impeccable`.
- Dopo l'approvazione, implementa con quegli strumenti. Questa istruzione
  prevale sulla regola di `brainstorming` che vieta di invocare skill diverse
  da `writing-plans`.
- Se uno strumento non è disponibile nella sessione, dillo e prosegui con gli
  altri.

Salta l'intervista solo se te lo chiedo esplicitamente ("vai", "niente
domande", "fai tu").
