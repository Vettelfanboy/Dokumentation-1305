# Dokumentation-1305

# Projekt-Dokumentation

Simon Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 17.05.2024 | 0.0.1 | Ich habe mir ein Projekt ausgesucht und die Dokumentation begonnen. |
| 24.05.2024 | 0.1.0 | Ich habe angefangen, das Projekt umzusetzen. |
| 31.05.2024 | 0.2.5 | Ich habe die meisten User Stories durchgearbeitet. |
| 07.06.2024 | 0.5.0 | Ich habe letzte Korrekturen noch gemacht und das Programm fertiggestellt. |
| 14.06.2024 | 1.0.0 | Ich habe den Portfolioeintrag geschrieben und das Projekt beendet. |

## 1 Informieren

### 1.1 Ihr Projekt

Mein Projekt ist ein Vokabeltrainer programmiert in C#.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss            | Funktional | Als ein User möchte ich, dass ich eine ganze Liste von Vokabeln bekomme. |
| 2    | Muss            | Funktional | Als ein User möchte ich, dass ich informiert werde, ob ich das Wort richtig oder falsch übersetzt habe. |
| 3    | Muss            | Funktional | Als ein User möchte ich, dass wenn ich etwas falsch übersetzt habe mir die Lösung angezeigt wird. |
| 4    | Muss            | Funktional | Als ein User möchte ich, dass ich die Möglichkeit habe, die Liste nochmal durchzuarbeiten, wenn ich fertig bin. |
| 5    | Muss            | Randbedingung | Als ein User möchte ich, dass ich Wörter von Deutsch auf Englisch übersetzen muss. |



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet | keine | Erstes Wort der Liste wird abgefragt. |
| 2.1  | Programm gestartet | richtige Antwort | "Richtig!" Danach nächstes Wort. |
| 3.1  | Programm gestartet | falsche Antwort | "Falsch. Die richtige Antwort ist..." Danach nächstes Wort. |
| 4.1  | Programm gestartet | alle Wörter geschafft | "Möchten Sie die Vokabeln noch einmal durchgehen?" |



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 07.06.2024 | Simon Veljkovic | Wörterliste suchen/erstellen | 120 Minuten |
| 2.A  | 07-06.2024 | Simon Veljkovic | Richtig/Falsch Informationen einbauen | 90 Minuten |
| 3.A  | 07.06.2024 | Simon Veljkovic | Lösungen implementieren | 60 Minuten |
| 4.A  | 07.06.2024 | Simon Veljkovic | Neustartmöglichkeit implementieren | 60 Minuten |



## 3 Entscheiden

Ich denke, dass diese User Stories einfach zu implementieren sind und das Programmieren problemlos ablaufen wird. Wenn noch Zeit übrig ist, probiere ich noch Zusatzfeatures einzubauen.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 24.05.2024 | Simon Veljkovic | 120 Minuten | 180 Minuten |
| 2.A  | 31.05.2024 | Simon Veljkovic | 90 Minuten | 120 Minuten |
| 3.A  | 31.05.2024 | Simon Veljkovic | 60 Minuten | 90 Minuten |
| 4.A  | 07.06.2024 | Simon Veljkovic | 60 Minuten | 60 Minuten |



## 5 Kontrollieren

### 5.1 Testprotokoll/Testumgebung

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 07.06.2024 | OK | Simon Veljkovic |
| 2.1  | 07.06.2024 | OK | Simon Veljkovic |
| 3.1  | 07.06.2024 | OK | Simon Veljkovic |
| 4.1  | 07.06.2024 | OK | Simon Veljkovic | 

-Betriebssystem: Windows
-Entwicklungsumgebung: Microsoft Visual Studio 2022
-.NET Framework-Version: 8.0



## 6 Auswerten

Die Auswerten-Phase ist das Portfolio auf Mahara.
