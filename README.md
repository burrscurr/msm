# Mathematisch-Stochastische Modelle: Markovketten und Monte-Carlo-Simulationen

(English summary: This repository contains notes from a class about Markov
chains and Monte-Carlo simulation at [HTW Dresden](https://htw-dresden.de))

<hr>

Skript für das Fach Mathematisch-Stochastische Modelle: Markovketten und
Monte-Carlo-Simulationen an der [HTW Dresden](https://htw-dresden.de). Es gibt
kein offizielles Skript für das Fach (wtf?).

Das Skript ist keine 1:1-Mitschrift aus der Vorlesung, sondern ist möglichst
pragmatisch und verständnisorientiert. Derzeit umfassen die meisten Abschnitte
vor allem die Definitionen und Sätze, für die Zukunft wären aber weitere
Beispiele, Erklärungen und Beweise cool.

## Fortschritt

- ⭕ Grundlagen der Wahrscheinlichkeitstheorie
- ✅ ├ Grundbegriffe
- ✅ ├ Unabhängigkeit, bedingte Wahrscheinlichkeit
- ✅ ├ Zufallsvektoren
- ✅ ├ Erwartungswert, Varianz
- ⭕ └ Covarianz, Korrelationskoeffizient
- ✅ Wahrscheinlichkeitsverteilungen
- ✅ ├ Diskrete Verteilungen
- ✅ └ Stetige Verteilungen
- ⭕ Erzeugung von Zufallszahlen
- ⭕ ├ Inversionsmethode (diskret)
- ✅ ├ Inversionsmethode (stetig)
- ✅ ├ Annahme-Verwerfungs-Methode
- ✅ ├ Importance Sampling
- ✅ ├ Box-Muller-Polarmethode
- ⭕ ├ Erzeugung von Zufallsvektoren
- ⭕ └ Mehrdimensionale Normalverteilung
- ⭕ Monte-Carlo (Skriptausschnitt in OPAL verfügbar)
- ⭕ ├ Zentraler Grenzwertsatz
- ⭕ ├ Satz von Moivre-Laplace
- ⭕ └ Anwendungsbeispiele
- ⭕ Markov-Ketten
- ✅ ├ Definition
- ✅ ├ Zustandsklassen
- ✅ ├ Rückkehreigenschaften
- ✅ ├ Langzeitverhalten
- ✅ ├ Reversible ergodische Markovketten
- ✅ ├ Markovketten mit unendlichem Zustandsraum
- ⭕ └ Markovketten in stetiger Zeit
- ⭕ Markov-Chain-Monte-Carlo
- ⭕ ├ Konzept
- ⭕ ├ Anwendungsbeispiele
- ⭕ └ Metropolis-Algorithmus

## Mitmachen

Das Skript wird mit `pdflatex` erstellt. Am einfachsten wird das Makefile
verwendet:

```
cd src
make
```

Erweiterungen und Korrekturen des Skripts sind sehr erwünscht und können als
Issues/Pull requests erstellt werden.
