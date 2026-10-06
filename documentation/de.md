<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · de · no clinical/professional/rights approval -->

# Ejektionsfraktion (Teichholz) und Verkürzungsfraktion

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/fracao-de-ejecao-teichholz)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Linksventrikulärer diastolischer Durchmesser

`ddve`

cm · Bereich: 2–9

### Linksventrikulärer systolischer Durchmesser

`dsve`

cm · Bereich: 1–8

## Fassung der Methode

Teichholz 1976: 7 D³/(2,4+D); EF und lineare Volumina; ASE/EACVI 2015 und geometrische Grenzen

## Dokumentierte Formel

Volumen (Teichholz) = 7 ÷ (2,4 + D) × D³ (D in cm, Volumen in mL)

Ejektionsfraktion = (EDV − ESV) ÷ EDV × 100

Verkürzungsfraktion = (LVEDD − LVESD) ÷ LVEDD × 100

## Grenzen und Population

Die Teichholz-Schätzung hängt von der geometrischen Beziehung zwischen Ventrikeldurchmesser und -volumen ab. In der Originalstudie war die Übereinstimmung ohne Asynergie gut und bei Asynergie schlecht. Koronare Krankheit mit möglicher regionaler Veränderung erfordert Vorsicht; die aus einem Durchmesser berechnete Fraktion ersetzt keine zur Ventrikelgeometrie geeigneten Methoden.

## Referenzen

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Erhaltene Ejektionsfraktion

| Ergebnisdetails | |
| --- | --- |
| Enddiastolisches Volumen | 118 mL |
| Endsystolisches Volumen | 41 mL |
| Schlagvolumen | 77 mL |
| Verkürzungsfraktion | 36% |

