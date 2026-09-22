# Prove-skills

Repository per provare le skill di Claude Code.

## Skill installate

| Skill | Origine | Che cosa fa |
| --- | --- | --- |
| `hallmark` | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) (MIT) | Skill di design anti-slop: costruisce interfacce nuove, più i verbi `audit`, `redesign` e `study`. |
| `brainstorming` | [obra/superpowers](https://github.com/obra/superpowers) (MIT) | Ti intervista una domanda alla volta, riassume, propone approcci e aspetta l'approvazione prima di scrivere codice. |
| altre skill di superpowers | [obra/superpowers](https://github.com/obra/superpowers) (MIT) | `writing-plans`, `executing-plans`, `subagent-driven-development`, `test-driven-development`, `systematic-debugging`, `verification-before-completion` e le altre a cui `brainstorming` rimanda. |

Le skill stanno in `.claude/skills/<nome>/` e Claude Code le carica da sé quando
si lavora dentro questo repository. Le skill di superpowers sono copiate dal
commit `5bf4e78` dell'upstream; la licenza è in
`.claude/skills/brainstorming/LICENSE.superpowers`.

`CLAUDE.md` impone l'ordine per il web development: prima l'intervista di
`brainstorming`, poi `hallmark`, `impeccable` e il connettore Originkit per la
parte visiva.

## Esempi

| Esempio | Skill | Note |
| --- | --- | --- |
| [`esempi/studio-commercialista/`](esempi/studio-commercialista/) | `hallmark` | Landing page di uno studio commercialista. Marquee Hero + tema Grid. Contenuti fittizi. |
| [`esempi/studio-commercialista-redesign/`](esempi/studio-commercialista-redesign/) | `hallmark redesign` | Stesso contenuto, Long Document + tema Atelier. Serve a misurare quanta varietà strutturale produce la skill. |

`.hallmark/log.json` è la memoria di progetto della skill: registra macrostruttura
e tema di ogni build, così la successiva ne sceglie di diversi.
