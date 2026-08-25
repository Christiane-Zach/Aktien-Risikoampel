# Aktien-Risikoampel

Dieses Projekt entstand als **Abschlussprojekt meiner Data-Science-Weiterbildung** und wurde als Gruppenarbeit entwickelt.

Ziel war die Entwicklung einer Aktien-Risikoampel, die anhand verschiedener Marktindikatoren einschätzt, wie hoch das aktuelle Risiko an den US-Aktienmärkten ist.

Dabei lag der Schwerpunkt nicht darauf, maximale Rendite zu erzielen, sondern Risiken frühzeitig zu erkennen und insbesondere größere Kursverluste zu begrenzen.

## Zielsetzung

Für die Risikoampel wurden insgesamt **36 Hypothesen** zu verschiedenen Marktindikatoren formuliert und anhand historischer Daten überprüft.

Untersucht wurden insbesondere:

* gleitende Durchschnitte
* Marktbreite
* Put/Call Ratio
* Volatilitätsindizes
* Advancing / Declining Stocks and Volume

Die Hypothesen wurden anhand verschiedener US-Aktienindizes getestet:

* S&P 500
* Dow Jones
* NASDAQ 100
* Russell 2000

## Bewertungsgrößen

Der zentrale Fokus lag auf der Risikominimierung.

Dafür wurde insbesondere der **Maximum Drawdown** betrachtet, also der größte zwischenzeitliche Wertverlust innerhalb eines betrachteten Zeitraums.

Zusätzlich wurde für jede Hypothese auch die erzielte Rendite berücksichtigt, um Risiko und Ertrag gemeinsam beurteilen zu können.

## Vorgehensweise

Die einzelnen Indikatoren wurden zunächst getrennt untersucht.

Für jeden Bereich wurden verschiedene Hypothesen aufgestellt, getestet und hinsichtlich Risiko und Rendite bewertet.

Die entsprechenden Analysen befinden sich in den jeweiligen Ordnern:

* `Advancing Declining Stocks and Volume`
* `Gleitender Durchschnitt`
* `Marktbreite`
* `Put-Call-Ratio`
* `Volatilitätsindizes`

Die Analysen wurden überwiegend in **Jupyter Notebooks** durchgeführt.

## Kombinierte Risikoampel

Aus den vielversprechendsten Hypothesen wurden anschließend konkrete Handelssignale abgeleitet.

Diese Signale wurden kombiniert und erneut bewertet, um daraus die finale Risikoampel zu entwickeln.

Die entsprechenden Analysen befinden sich im Ordner:

`kombinierte Risikoampel`

## Streamlit Dashboard

Die Ergebnisse wurden anschließend in einem interaktiven Streamlit-Dashboard aufbereitet.

[Zur Aktien-Risikoampel](https://aktien-risikoampel.streamlit.app/)

Der zugrunde liegende Code befindet sich in diesem Repository im Ordner:

`Streamlit Dashboard`

## Einsatz von KI

Im Rahmen des Abschlussprojekts haben wir **Claude Code bewusst als Entwicklungswerkzeug eingesetzt**.

Ziel war nicht, die fachliche Arbeit an die KI auszulagern, sondern den praktischen Umgang mit KI-gestützter Softwareentwicklung zu erproben.

Dazu gehörten unter anderem:

* Unterstützung bei der Code-Erstellung
* Unterstützung beim Refactoring
* Fehlersuche und Debugging
* Strukturierung einzelner Arbeitsschritte
* Diskussion möglicher Lösungsansätze

Die fachlichen Fragestellungen, Hypothesen, Bewertungen und Entscheidungen wurden im Team entwickelt und überprüft.

## Teamprojekt

Die Aktien-Risikoampel entstand als Gruppenarbeit.

Das Repository enthält den vollständigen Projektstand, den ich für meine eigene Dokumentation des Abschlussprojekts übernommen habe.

## Abschlusspräsentation

Die Abschlusspräsentation des Projekts befindet sich im Ordner:

`Abschlusspräsentation`

Sie gibt einen kompakten Überblick über Fragestellung, Vorgehensweise und Ergebnisse des Projekts.

## Technologien

* Python
* Jupyter Notebook
* pandas
* Streamlit
* Datenanalyse
* Datenvisualisierung
* Finanzmarktdaten
* Claude Code

## Hinweis

Dieses Projekt dient der Analyse historischer Marktdaten und der Entwicklung einer datenbasierten Risikoindikatorik.

Es stellt **keine Anlageberatung oder Handlungsempfehlung** dar.
