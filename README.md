Mensch-Computer-Interaktion Übungsblatt 2 Sommersemester 2018 bei Dr. Bastian Pfleging an der Universität Stuttgart . Aufgabenstellung war wie folgt:
## B) Programmieren eines Reaktionszeitexperiments [index.html](index.html)

In dieser Aufgabe werden einfache kognitive Prozesse untersucht. Dazu wird die
Reaktionszeit gemessen, um bestimmte Stimuli wahrzunehmen oder
Entscheidungen zu treffen.

Als Basis für diese Aufgabe stellen wir ein Beispielprogramm (JavaScript) zur
Verfügung, welches Reaktionszeiten für einfache Stimuli messen kann.
Beispielsweise lässt sich damit messen, wie lange ein Benutzer braucht, um eine
Taste zu betätigen, nachdem sich ein Farbstimulus auf dem Bildschirm verändert
hat. Das Programm unterstützt die folgenden Funktionalitäten:


* Der Benutzer startet das Experiment mit dem Drücken der Leertaste.
* An einem beliebigen Zeitpunkt (zwischen 2 und 6 Sekunden) verändert
sich die Farbe eines Textfeldes. Hierbei handelt es sich um den
Beispielstimulus.
* Das Programm misst die Zeit nach dem Auftauchen des Stimulus bis der
Benutzer die Leertaste drückt.
* Die gemessene Zeit wird in einem Array gespeichert und auf dem
Bildschirm dargestellt. Danach beginnt die nächste Wiederholung.


* Wenn der Benutzer die Taste ‚a‘ betätigt, endet das Experiment und die
Ergebnisse des Experiments (Mittelwert der benötigten Reaktionszeit,
Standardabweichung) werden auf dem Bildschirm dargestellt.
* Durch das erneute Betätigen der Leertaste wird ein neues Experiment
gestartet.
Das Beispielprogramm wird im Ilias hochgeladen und ist auch am Ende des
Übungsblattes zu finden.

**Bitte beachten Sie die folgenden Hinweise für alle Unteraufgaben:**


1. Für die Bearbeitung der Teilaufgaben können einzelne Programme
erstellt werden. Als Basis für die Programme kann das Beispielprogramm
in JavaScript (https://www.w3schools.com/js/) verwendet werden.
Alternativ kann auch die Programmiersprache Processing
(https://processing.org/) verwendet werden.
2. Die Reihenfolge der dargestellten Stimuli soll zufällig erfolgen.
3. Nachdem ein Stimulus erkannt wurde, soll für eine zufällige Dauer von 2
bis 6 Sekunden kein Stimulus dargestellt werden. Anschließend soll der
nächste Stimulus dargestellt werden.

## B.1) Einfaches Reaktionszeit-Experiment [b_1.html](b_1.html) ⚠️ Audioausgabe ist evtl. sehr laut


Es sollen zwei unterschiedliche Stimuli dargestellt werden, um die
Reaktionszeiten messen und vergleichen zu können.
a. Es soll ein auditiver Stimulus in Form eines Tierlauts dargestellt
werden.
b. Es soll ein visueller Stimulus in Form eines Bildes dargestellt werden.
Der Benutzer soll eine Taste betätigen (z.B. die Leertaste), sobald ein Stimulus
dargestellt wurde. Nach der oben beschriebenen Pause soll der nächste
Stimulus dargestellt werden. Für Wiederholungen der Stimuli soll dasselbe
Bild / derselbe Laut benutzt werden. Nach Beendigung des Experiments sollen
für jede Stimulusart (a und b) als Ergebnisse die mittlere Reaktionszeit, die
Standardabweichung und die Fehlerrate (z.B. wenn der Benutzer die Taste
betätigt, ohne dass ein Stimulus dargestellt wurde) angezeigt werden.

## B.2) Entscheidungsreaktionszeit-Experiment [b_2.html](b_2.html)


Stellen Sie einen binären Stimulus dar: Verwenden Sie gefüllte Dreiecke als Go-
Stimulus und gefüllte Kreise als No-Go-Stimulus. Die Größe der dargestellten
Dreiecke und Kreise soll zwischen 150 und 350 Pixeln liegen und zufällig
bestimmt werden. Beide Stimuli sollen mit derselben Wahrscheinlichkeit
zufällig ausgewählt werden. Der Benutzer soll dazu angeleitet werden die
Leertaste nur dann zu betätigen, wenn ein Dreieck (Go) dargestellt wird.
Betätigt der Benutzer die Leertaste während ein Kreis (No-Go) dargestellt
wird, wird dies als Fehler gezählt. Die Ergebnisse des Experiments sollen die
mittlere Reaktionszeit, die Standardabweichung (SD), sowie die Fehlerrate
beinhalten.

## B.3) Darstellung eines komplexen Stimulus, der wahr oder falsch sein kann [b_3.html](b_3.html)


Als Stimulus werden verschiede Tierarten in Wortform verwendet. Die
Aufgabe der Probanden besteht darin, aufgrund des Namens zu entscheiden,
ob es sich um ein Säugetier handelt oder nicht. Falls es sich bei dem
dargestellten Stimulus um ein Säugetier handelt, soll der Benutzer die Taste
‚t‘ betätigen (für „true“). Falls es sich bei dem dargestellten Stimulus nicht um
ein Säugetier soll der Benutzer die Taste ‚f‘ (für „false“) betätigen. Das
Betätigen der falschen Taste wird als Fehler gewertet. Die Ergebnisse des
Experiments sollen die mittlere Entscheidungszeit, die Standardabweichung
(SD), sowie die Fehlerrate beinhalten.

## B.4) Kreativ-Aufgabe [b_4.html](b_4.html)


Denken Sie sich ein kurzes Spiel aus, welches eines der oben beschriebenen
Experimente untersucht und implementieren Sie dieses als eigenes Programm.
Nutzen Sie dabei auch Ihr Wissen über Gamification.
