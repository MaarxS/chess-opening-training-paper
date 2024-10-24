Wie Benutzt Man Diese Vorlage?
==========================

1. Entsprechende �nderungen in main.tex vornehmen
Es geht hier um Titel, Autor, usw. und dito f�r die 
ehrenw�rtliche Erkl�rung

2. Im Verzeichnis ./images kannst Du Deine Abbildungen abspeichern

3. Schreibe Deine Kapitel im Verzeichnis ./content/chapter 
und gebe sie Nummer als Namen: 01.tex usw.

4. Schreibe Deine Zusammenfassung in Datei ./content/abstract.tex

5. Arbeite dito in acronyms.tex, glossary.tex und appendix.tex

Wenn Du ein sauberes, aktuelles PDF mit korrekten Literaturverweisen
und intertextuelle Verweisen generieren m�chtest, dann gehe wie folgt vor:
1. F�hre "pdfLatex" aus auf Datei main.tex
2. F�hre "biber" aus auf Datei main.tex
3. F�hre nochmal "pdfLatex aus auf Datei main.tex


An dieser Stelle noch den Hinweis, dass eine bessere, aber auch etwas komplexere, 
Fassung dieser Vorlage downloadbar ist unter:
	 https://github.com/schnes4/dhbw-heidenheim-latex-template
	 
Viel Erfolg!
