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

## Rapporto con `hallmark`

`hallmark` resta la skill per la parte visiva, ma viene **dopo** l'intervista:

- Le risposte dell'intervista (pubblico, uso, tono) valgono come brief di
  `hallmark`, quindi non ripetere le sue domande se ho già risposto.
- Tema e macrostruttura scelti con `hallmark` entrano nel design che mi presenti
  per l'approvazione.
- Dopo l'approvazione, per il codice visivo applica le regole di `hallmark`.
  Questa istruzione prevale sulla regola di `brainstorming` che vieta di
  invocare skill diverse da `writing-plans`.

Salta l'intervista solo se te lo chiedo esplicitamente ("vai", "niente
domande", "fai tu").
