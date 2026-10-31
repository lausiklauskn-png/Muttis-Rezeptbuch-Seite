**🔬 Regel: Forschung nur in Kimhub (Klaus 2026-10-31: „einheitlich alles in Kimhub … in den einzelnen Repos soll keine Forschungseinträge sein“):** jeder Forschungseintrag (Sitzungs-Befunde, Messungen, Stunden-Auswertungen, Forschungsnotizen) kommt nach **Kimhub `forschung/messungen/`**; in diesem Repo werden keine Forschungseinträge geführt und keine Forschungsdateien angelegt. Öffentliche Forschungs**aufgaben** stehen in Sage-Protokol.

# Muttis-Rezeptbuch-Seite — Sitzungs-Anker

**Dieses Repo ist (noch) leer** — es enthält nur `README.md`, `LICENSE` und
`RECHTE.md`, keine App und keinen Code. Stand: 2026-08-22.

Wer hier etwas bauen soll, **fragt vorher Klaus**, wofür das Repo gedacht ist. Ein
leeres Repo ist kein Freibrief, es mit etwas zu füllen, das sich plausibel anhört.

## Netzweit

Freibrief zum Selbst-Mergen · Gerätename · frisch von `origin/main` vor jeder Arbeit ·
Ton · kein PII · Ehrlichkeit stehen **einmal** in
**[`Sage-Protokol/docs/NETZWEIT.md`](https://github.com/lausiklauskn-png/Sage-Protokol/blob/main/docs/NETZWEIT.md)**.

```bash
git fetch origin --quiet && git checkout -B <branch> origin/main
git push -u origin refs/heads/<branch>:refs/heads/<branch>
git diff --stat origin/main origin/<branch>     # leer = der PR wäre leer
```
