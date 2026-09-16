# Prove-skills

Repository per provare le skill di Claude Code.

## Skill installate

| Skill | Origine | Che cosa fa |
| --- | --- | --- |
| `hallmark` | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) (MIT) | Skill di design anti-slop: costruisce interfacce nuove, più i verbi `audit`, `redesign` e `study`. |

Le skill stanno in `.claude/skills/<nome>/` e Claude Code le carica da sé quando
si lavora dentro questo repository.

## Esempi

| Esempio | Skill | Note |
| --- | --- | --- |
| [`esempi/studio-commercialista/`](esempi/studio-commercialista/) | `hallmark` | Landing page di uno studio commercialista. Marquee Hero + tema Grid. Contenuti fittizi. |

`.hallmark/log.json` è la memoria di progetto della skill: registra macrostruttura
e tema di ogni build, così la successiva ne sceglie di diversi.
