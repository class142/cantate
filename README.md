# cantate &rarr; Jäger
WLAN-Fernsteuerung für kabelgebundene Liedanzeiger, um die Umrüstung auf den Zahlengeber "ZG-08 Funk" für gut 1000€ zu umgehen.

Die Fernsteuerung basiert auf einem ESP8266-Modul (NodeMCU).
Per Relaiskarte kann zwischen altem Zahlengeber und WLAN-Steuerung umgeschalten werden.

Das ESP-01 öffnet ein verschlüsseltes WLAN mit Captive-Portal, das auf der Captive-Seite die 
Eingabe von Nummern für den Liedanzeiger erlaubt. Der entsprechende Quellcode findet sich in 
Liedanzeiger.ino und kann mit der Arduino-IDE (mit passenden Board-Package) und einem USB-to-
UART-Converter installiert werden.
