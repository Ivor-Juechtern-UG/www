---
title: Tod durch Qualität
draft: true
authors: 
image: images/mutation-tests.png
explanation: Ein Lauf von Mutationstests auf sieben Kernen gleichzeitig; die Zahl in Klammern ist der Kern. Jede Zeile ist ein Mutant, eine kleine Änderung im Code, etwa &laquo; &lt; &raquo; zu &laquo; &lt;= &raquo;, mit seiner Nummer unter den Mutanten seiner Datei. &laquo; Killed &raquo;: ein Test hat die Änderung bemerkt. &laquo; Survived &raquo;: kein Test. &laquo; No code change &raquo;: der Mutant ist dasselbe Programm wie das Original.
---

1971 erfand Richard Lipton die Mutationstests.

Er war damals Student. Die Idee ist einfach: Man pflanzt einen kleinen Fehler in den Code, lässt die Tests laufen und schaut, ob sie ihn bemerken. Ein Test, der ihn bemerkt, tötet den Mutanten. Ein Mutant, den kein Test bemerkt, überlebt und zeigt, wo die Tests blind sind.

1978 veröffentlichten Richard DeMillo, Richard Lipton und Frederick Sayward die Methode: __Hints on Test Data Selection: Help for the Practicing Programmer__, in IEEE Computer.

Fünfzig Jahre lang blieb sie meist eine Idee. Jeder Mutant verlangt, dass alle Tests noch einmal laufen, und jeder Überlebende verlangt einen neuen Test, den jemand schreiben muss.

# Zielgruppe

Folgt.

# Das Vokabular des Todes

Folgt: Mutanten werden getötet, sie überleben; die Sprache der Methode ist die Sprache des Todes.

# Ihrer Zeit voraus

Folgt: Es fehlte die Technik, die Idee zu tragen. Heute schreiben Droiden die Tests, und die Kerne, die nachts stillstehen, lassen sie laufen.

# Tod durch Qualität

Folgt.
