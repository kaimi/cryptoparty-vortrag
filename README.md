# cryptoparty-vortrag #

(modularer) Vortrag für Cryptoparties

## PDF-Download ##

Fertige PDFs finden sich unter
[releases](https://github.com/kaimi/cryptoparty-vortrag/releases
"cryptoparty-vortrag: releases").

## selbst kompilieren ##

Voraussetzung für das selbständige Erzeugen der PDF-Folien sind folgende
TeXlive-Pakete:

* xelatex
* beamer
* babel
* babel-german
* eu1enc
* xtlxtra

Aus [`vortrag.tex`](https://github.com/kaimi/cryptoparty-vortrag/blob/master/vortrag.tex
"vortrag.tex") lassen sich die Folien, aus
[`notizen.tex`](https://github.com/kaimi/cryptoparty-vortrag/blob/master/notizen.tex
"notizen.tex") die Notizen für den Speaker generieren. Wenn ich irgendwann mal
nicht so faul bin, mache ich aus dem gammeligen
[`build.sh`](https://github.com/kaimi/cryptoparty-vortrag/blob/master/build.sh
"build.sh") noch mal was ordentliches. In der Zwischenzeit kann ich
[vim-latex](http://vim-latex.sourceforge.net/ "Sourceforge: vim-latex")
empfehlen.

### Daten ändern ###

In der Datei
[`config.tex`](https://github.com/kaimi/cryptoparty-vortrag/blob/master/config.tex
"config.tex") lassen sich einige Daten für einen eigenen Vortrag überschreiben.

### Kapitelauswahl ###

Durch Löschen einzelner Einträge aus
[`kapitel.tex`](https://github.com/kaimi/cryptoparty-vortrag/blob/master/kapitel.tex
"kapitel.tex") lassen sich die entsprechenden Abschnitte aus dem generierten PDF
ausnehmen. Nicht immer braucht man alle Kapitel.

Neue Kapitel folgen, sobald ich die Muße dazu habe und/oder sie brauche.
Natürlich nehme ich da auch gerne Contributions an.

## beitragen ##

Pull Requests nehme ich immer gerne. Genau wie Grafiken und Visualisierungen für
die Folien – ich bin Coder, kein Designer.

Fast genauso gerne behebe ich Fehler. Und sei es nur ein fehlendes Paket unter
den Kompiliervoraussetzungen.

## Lizenz ##

Das Material steht unter
[CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/
"Creative Commons: CC-BY-SA 3.0").
