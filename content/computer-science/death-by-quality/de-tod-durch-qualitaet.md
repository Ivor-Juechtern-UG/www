---
title: Tod durch Qualität
draft: true
authors: 
image: images/mutation-tests.png
explanation: Ein Lauf von Mutationstests auf sieben Kernen gleichzeitig; die Zahl in Klammern ist der Kern. Jede Zeile ist ein Mutant, eine kleine Änderung im Code, etwa &laquo; &lt; &raquo; zu &laquo; &lt;= &raquo;, mit seiner Nummer unter den Mutanten seiner Datei. &laquo; Killed &raquo;: ein Test hat die Änderung bemerkt. &laquo; Survived &raquo;: kein Test.
---

1971 erfand Richard Lipton die Mutationstests.

Er war damals Student. Die Idee ist einfach: Man pflanzt einen kleinen Fehler in den Code, lässt die Tests laufen und schaut, ob sie ihn bemerken. Ein Test, der ihn bemerkt, tötet den Mutanten. Ein Mutant, den kein Test bemerkt, überlebt und zeigt, wo die Tests blind sind.

1978 veröffentlichten Richard DeMillo, Richard Lipton und Frederick Sayward die Methode: __Hints on Test Data Selection: Help for the Practicing Programmer__, in IEEE Computer.

Fünfzig Jahre lang blieb sie meist eine Idee. Jeder Mutant verlangt, dass alle Tests noch einmal laufen, und jeder Überlebende verlangt einen neuen Test, den jemand schreiben muss.

# Zielgruppe

Dieser Artikel richtet sich an Entwickler, die ihre Tests inzwischen von Droiden schreiben lassen, und an alle, die entscheiden, wie viel Testen genug ist.

# Das Vokabular des Todes

Die Methode spricht die Sprache von Leben und Tod. Ein Mutant entsteht aus einer kleinen Änderung: aus &laquo; &lt; &raquo; wird &laquo; &lt;= &raquo;, aus &laquo; true &raquo; wird &laquo; false &raquo;, aus einer 1 eine 2. Die Tests laufen. Entweder sie bemerken es, dann wird der Mutant __getötet__, oder niemand bemerkt es, dann __überlebt__ er.

Manche Mutanten können nie sterben. Der Lauf markiert sie mit &laquo; no code change &raquo;: Die Änderung ergibt dasselbe Programm, und es gibt nichts, was ein Test bemerken könnte. Man nennt sie äquivalente Mutanten. Sie sind unsterblich und kosten so viel Zeit wie die anderen.

Jeder Überlebende ist eine Frage. Im Bild: Zeile 52, aus &laquo; &lt; &raquo; wurde &laquo; &lt;= &raquo;, überlebt. Irgendwo kann eine Grenze einen Schritt weiter außen liegen, und kein Test stört sich daran.

# Ihrer Zeit voraus

Mutationstests sind eine Idee, die vor der Technik kam, die sie tragen konnte. Der Biologe Stuart Kauffman nannte den nächsten erreichbaren Schritt das benachbarte Mögliche, _the adjacent possible_: Eine Idee wird Wirklichkeit, sobald die Schritte neben ihr existieren.

Für Mutationstests fehlten zwei Schritte. Das Laufen: Eine Datei im Bild hat 398 Mutanten, und jeder verlangt, dass die Tests noch einmal laufen. Das Schreiben: Jeder Überlebende verlangt einen neuen Test, und jemand muss ihn schreiben.

Beide Schritte sind jetzt da. Die Kerne, die nachts zu Hause oder im Büro stillstehen, lassen die Tests laufen. Droiden schreiben die neuen. Qualitätsansätze, die fünfzig Jahre gewartet haben, sind billig geworden.

# Tod durch Qualität

Billig ist nicht umsonst. Ein Droide schreibt für jeden Überlebenden einen Test, unermüdlich, wie der Besen des Zauberlehrlings Wasser trägt. Die Tests wachsen schneller als der Code.

Drei Tode folgen:

1. __Tod durch Lesen.__ Tests zu schreiben kostet nichts mehr; sie zu lesen kostet immer noch einen Menschen. Jeder Test ist etwas, das jemand verstehen muss, bevor er den Code ändert.
2. __Tod durch Erstarren.__ Ein Test, der nur geschrieben wurde, um einen Mutanten zu töten, hält den Code oft genau so fest, wie er ist. Die nächste Änderung, so gut sie sein mag, tötet ein Dutzend Tests, und niemand traut sich, sie zu machen.
3. __Tod durch Unsterbliche.__ Äquivalente Mutanten lassen sich nicht töten. Sie zu jagen ist Arbeit ohne Ende.

Die Antwort sind nicht weniger Tests, sondern eine Entscheidung darüber, wofür Qualität da ist. Töte die Mutanten dort, wo ein Fehler weh täte: beim Geld, bei der Sicherheit, an den Rändern einer Grenze. Lass andere bewusst überleben und schreib auf, warum. Ein Überlebender ist eine Frage, kein Befehl.

# Quellen

* R. A. DeMillo, R. J. Lipton, F. G. Sayward, __Hints on Test Data Selection: Help for the Practicing Programmer__, IEEE Computer 11(4), 1978.
* S. Kauffman, _the adjacent possible_, bekannt gemacht von S. Johnson, __Where Good Ideas Come From__, 2010.
