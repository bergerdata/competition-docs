---
title: "Question: Dropdown"
linkTitle: "Question: Dropdown"
date: 2020-01-05
description: >
  Lückentext mit Dropdown-Feldern
---

## Beschreibung

In einen Text lassen sich beliebig viele Dropdowns mit Antwortmöglichkeiten unterbringen. Der Teilnehmer muss die richtigen Wörter mittels der Dropdowns wählen.

### Vorschau

{{< imgproc dropdown Fit "700x700" >}}
{{< /imgproc >}}


## Aufbau

An den Stellen im Content-Text wo die Dropdowns erscheinen sollen, müssen Platzhalter mit eckigen Klammern "[NAME]" vergeben werden.
 
Genau wie bei Multiple-Choice müssen alle Antwortmöglichkeiten als "Answers" angelegt werden. Da es im Text mehrere Platzhalter geben kann, muss dessen zugehörigkeit über das Feld "Collection" bei der Antwort festgelegt werden. 

In Beispiel gibt es 2 Platzhalter für Dropdowns: **[A]** und **[Jahr]**. Der Name des Platzhalters darf beliebig sein - er muss nur mit dem Namen der "Collection" der Antwort übereinstimmen.

{{< imgproc dropdown_author Fit "700x700" >}}
{{< /imgproc >}}

### Content

- Title: Titel der Frage
- Details: Detailtext zur Frage. Muss die Collection-Platzhalter in eckigen Klammern enthalten.

### Answers

- Title: Titel der Antwort
- Details: Detailtext zur Antwort
- Correct?: Markieren, wenn es die richtige Antwort ist
- Collection: Verknüpft die Antwort mit dem jeweiligen Platzhalter im Text
- Score: Punktzahl die vergeben wird bei gewählter Antwort 
