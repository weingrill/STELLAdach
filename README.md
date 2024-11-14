# STELLA Dachsteuerung

* Host Name: CX-284792
* AMS Net-Id: 5.40.71.146.1.1
* IP: 161.72.132.100
Zum Erstellen einer neuen Route muss auf der PLC eine remote route "None"
angelegt werden.


## Features

* Dach öffnet auf Setzen OpenRoof1 bzw. OpenRoof2 Bits.
* Dach schließt durch Setzen des CloseRoof1 Bits bzw. CloseRoof2 Bits.
* Öffnen und Schließen ist in jeder Lage möglich, auch Fahrtrichtungswechsel.
* Dach schließt automatisch bei Schlechtwetter:
  * Regensensor digital an,
  * >80% Luftfeuchtigkeit,
  * Dust > 0.01 µg/m³, oder
  * Wind > 10 m/s
* Horn geht für 2 Sekunden an, wenn das Dach bewegt wird.
* Lichttaster schaltet für eine Stunde das Licht an, wenn im Automodus betätigt.
* Lichttaster schaltet das Licht dauerhalft an, wenn im manuellen Modus betätigt.
* Licht schaltet ab, wenn das Dach geoeffnet wird.
* Entfeuchter wird eingeschalten bei Dach geschlossen und
  * Luftfeuchtigkeit innen > aussen, oder
  * Luftfeuchtigkeit innen > 50%


## TODO
- [ ] Environment in eignen Task kapseln
