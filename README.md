# Eine-LED-pulsieren-lassen
Aufgabe: Eine LED soll pulsierend heller und dunkler werden. (Auch als engl. „faden“ bezeichnet)

Material: Arduino / eine LED / Ein Widerstand mit 330 Ohm / Breadboard / Kabel

Der Arduino ist ein digitaler Mikrocontroller. Er kennt an seinen Ausgängen nur „5 Volt an“ oder „5V aus“. Um die Helligkeit einer LED zu variieren, müsste man die Spannung jedoch variieren können. Zum Beispiel 5V wenn die LED hell leuchtet. 4 Volt, wenn sie etwas dunkler leuchtet usw. DAS GEHT AN DIGITALEN PINS ABER NICHT. Es gibt jedoch eine Alternative. Sie nennt sich Pulsweitenmodulation (PWM genannt). Die PWM lässt die 5V Spannung pulsieren. Die Spannung wird also im Millisekundenbereich ein und ausgeschaltet. Bei einer hohen PWM liegt das 5V Signal nahezu durchgehend am jeweiligen Pin an. Bei einer geringen PWM ist das 5V Signal kaum noch vorhanden (Da dies eine sehr kompakte Zusammenfassung ist, sollte man sich im Internet nach weiteren Erläuterungen umsehen). Mit dieser PWM kann man bei LEDs einen ähnlichen Effekt erreichen, als würde man die Spannung variieren. Nicht alle digitalen Pins am Board haben die PWM Funktion. Die Pins an denen die PWM funktioniert sind besonders gekennzeichnet, bspw. durch eine kleine Welle vor der Zahl mit der Pinnummer . Los geht’s!


Weitere Infos unter: https://funduino.de/
