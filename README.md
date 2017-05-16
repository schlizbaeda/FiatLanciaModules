ACHTUNG:

Dieses Repository stammt weder vom Automobilhersteller "FIAT S.p.A.",
noch vom zum FIAT-Konzern gehörenden Automobilzulieferunternehmen 
"Magneti Marelli S.p.A."! Die Verwendung dieser Namen durch mich dient
lediglich der leichteren Zuordnung für den Leser, wofür die hier 
präsentierte Anleitung und weitere Daten dienen sollen.

# FiatLanciaModules
EPROM-Programmierung der Module für den Fiat/Lancia-Tester

In der Datei FL-Module_programmieren.pdf befindet sich eine Anleitung, wie 
aus vorhandenen EPROM-Modulen für den F/L-Tester aus den 90er-Jahren(?)
- die Moduldaten ausgelesen
- die Module (zum Widerbeschreiben) gelöscht 
- die Module neu programmiert

werden können.

Dieses GitHub-Repository enthält alle Dateien zur Erstellung dieser Doku-
mentation mittels LaTeX im Hauptverzeichnis sowie in den Unterverzeichnissen
Bilder, Kapitel und Layout

# Erstellung der pdf-Datei mittels LaTeX unter Ubuntu im Terminalfenster
$ sudo apt-get install texlive-full

$ pdflatex FL-Module_programmieren.tex

Während der Erstellung erscheint die Meldung

    l.180 \caption
                      {{\FLTester} und Memory}           
    ? 
mit blinkendem Cursor. Hier über die Tastatur R ENTER eingeben.

$ pdflatex FL-Module_programmieren.tex

Dieser zweite Aufruf ist in LaTeX erforderlich, um das Inhaltsverzeichnis
und die Verlinkungen des Dokumentes korrekt zu erstellen.


# Nachbau
Der Nachbau inkl. Schaltplänen ist in FL-Module_programmieren.pdf beschrieben.
Im Verzeichnis Hardware befinden sich weitere Informationen für den Nachbau:
- Layoutdaten für EAGLE
- IC-Datenblätter
