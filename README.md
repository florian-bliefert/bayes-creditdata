# Predictive Analytics mit dem Bayes-Klassifizierer entdecken
Im Controller Magazin 05/23 habe ich einen Artikel veröffentlicht, in dem ich eine Einführung in Predictive Analytics gebe. Dazu verwende ich Daten aus dem UCI-Repository (https://archive.ics.uci.edu/dataset/144/stat-log+german+credit+data), um einen Bayes-Klassifizierer zu erstellen, der einen möglichen Kreditausfall vorhersagt.

Das ganze ist mit KNIME erstellt, hier sind alle notwendigen Dateien, um den Artikel am eigenen Rechner nachvollziehen zu können.

# HowTo
KNIME speichert seine Projekte in einem workspace, die heruntergeladene knwf-Datei muss also in den eigenen Workspace kopiert werden (KNIME weist beim öffnen darauf hin). Danach müssen die Pfade für die zwei Dateien, die KNIME einliest, angepasst werden:
- german.data
- dictionary.csv
Die Datei `dictionary.csv` habe ich aus der `german.doc`Datei aus dem Original-Download erstellt, damit die codierten Features sprechend sind.

# Lizenz
Das Projekt steht unter der Creative Common Lizenz CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de)
