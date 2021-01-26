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

- [ ] Grundlagen der Wahrscheinlichkeitstheorie
- [x] ├ Grundbegriffe
- [x] ├ Unabhängigkeit, bedingte Wahrscheinlichkeit
- [x] ├ Zufallsvektoren
- [x] ├ Erwartungswert, Varianz
- [ ] └ Covarianz, Korrelationskoeffizient
- [x] Wahrscheinlichkeitsverteilungen
- [x] ├ Diskrete Verteilungen
- [x] └ Stetige Verteilungen
- [ ] Erzeugung von Zufallszahlen
- [ ] ├ Inversionsmethode (diskret)
- [x] ├ Inversionsmethode (stetig)
- [x] ├ Annahme-Verwerfungs-Methode
- [x] ├ Importance Sampling
- [x] ├ Box-Muller-Polarmethode
- [ ] ├ Erzeugung von Zufallsvektoren
- [ ] └ Mehrdimensionale Normalverteilung
- [ ] Monte-Carlo (Skriptausschnitt in OPAL verfügbar)
- [ ] ├ Zentraler Grenzwertsatz
- [ ] ├ Satz von Moivre-Laplace
- [ ] └ Anwendungsbeispiele
- [ ] Markov-Ketten
- [x] ├ Definition
- [x] ├ Zustandsklassen
- [x] ├ Rückkehreigenschaften
- [x] ├ Langzeitverhalten
- [x] ├ Reversible ergodische Markovketten
- [x] ├ Markovketten mit unendlichem Zustandsraum
- [ ] └ Markovketten in stetiger Zeit
- [ ] Markov-Chain-Monte-Carlo
- [ ] ├ Konzept
- [ ] ├ Anwendungsbeispiele
- [ ] └ Metropolis-Algorithmus

## Mitmachen

Das Skript wird mit `pdflatex` erstellt. Am einfachsten wird das Makefile
verwendet:

```
cd src
make
```

Erweiterungen und Korrekturen des Skripts sind sehr erwünscht und können als
Issues/Pull requests erstellt werden.
