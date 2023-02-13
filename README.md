
# SEM-Master (Stand: 2023/02/13)

Dies ist eine Vorlage für kleinere Ausarbeitungen, etwa für Seminarvorträge (Handouts), Hausarbeiten oder kleinere Artikel. Die Vorlage eignet sich auch bestens, um sich in das LaTeX-System einzuarbeiten. Wer es etwas anspruchsvoller haben will: Bitte die `AGFA-Light`-Vorlage in [**AGFA-Master**](https://github.com/ugroh/AGFA-Master) nutzen. 

Über `Code` (grüner Kasten rechts oben) kann man sich die dort vorhandene ZIP-Datei auf den PC herunterladen und lokal nutzen. Alternative: Das System [**Overleaf**](https://www.overleaf.com) nutzen. In diesem Fall die ZIP-Datei als ein neues Projekt hochladen. 

## Literatur

* Eine gute Einführung in LaTeX ist [**l2kurz**](https://ftp.agdsn.de/pub/mirrors/latex/dante/info/lshort/german/l2kurz.pdf), die ich allen empfehlen kann. 

* Für die Eingabe von Mathematik die kurze, aber prägnante Übersicht [**AMS: Short Math Guide**](https://ctan.org/pkg/short-math-guide) nutzen. Aus meiner Sicht eine der besten Kurzeinführungen in den Formelsatz. 

* Wer sich intensiver mit LaTeX beschäftigen will: Auf [**Literatur zu LaTeX**](https://www.dante.de/dante-e-v/literatur/) findet man die Empfehlungen. 

## Aufbau der Vorlage

Nach dem Entpacken hat man Folgendes: 

* Im Stammverzeichnis befinden sich die Datei `SEM-Master.tex` als allgemeine Vorlage und `SEM-Beamer.tex` als Vorlage für Präsentationen mit der Beamer-Klasse.

* In `./preamble` findet sich die Datei `SEM-art.tex`, in der Layout usw. zu finden sind. Bitte diese Datei nicht ändern. Falls es spezielle Wünsche für Ergänzungen gibt, dann kann ich die gern einarbeiten.

* In der Datei SEM-defn.tex habe ich einige Definitionen vorgenommen, die ich für nützlich halte und die auch als Anhalt für eigene Definitionen genommen werden können. Weitergehende findet man in der o.g. Vorlage.

* Eigene Definitionen bitte **separat** in `My-defn.tex` eintragen und vor allem testen. 

* In `./content` findet sich die Dateien, in der man seinen Text eingeben soll und die via `\input{fn}` in die Hauptdatei übernommen wird. Bitte hier das Muster `ug-Master.tex` ansehen.

## Sonstiges 	 
	 
Bitte unbedingt die Datei `SEM-ReadMe.pdf` lesen und beherzigen, was dort steht. 
Diese findet sich im `./SEM-ReadMe` Ordner (inkl. der Datei `SEM-Master.pdf` und `SEM-Beamer.pdf`). 

Fragen,  Wünsche etc. bitte an **<ulgr@math.uni-tuebingen.de>**

## Ergänzungen:

* 2023/01/16
	- Kleinere Ergänzungen


	




