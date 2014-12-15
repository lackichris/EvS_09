Zusammenfassung von „Continous Integration“ 
=============
Quelle:[link](http://www.thoughtworks.com/continuous-integration)

„Räum alles weg“ damit du schneller Coden kannst!
---------------------


**lade deinen Code mindestens einmal am Tag hoch**

Je öfter du täglich deinen Code ins gemeinsame Repository lädst, umso besser – dann können automatische builds oder auch deine Kollegen schneller und früher Fehler finden.

**löse Probleme schnell**

Da du so oft und regelmäßig programmierst entdeckst du Fehler schneller. Das macht auf Dauer die Entwicklungskosten günstiger.


**mehr als nur ein Prozess**

stetiges Porgammieren erfordert einige wichtige Strategien.


*Methoden*

* mache dein build mit Selbsttests
* halte das build schnell
* teste in einem Klon der späteren Laufzeitumgebung
* habe ein einziges Repostitory 
* ....


*wie wird es gemacht*

* die Entwickler checken Code in ihren privaten Workspace aus
* wenn du fertig bist, commite deine Änderungen
* der CI-Server gibt Bescheid bei erfolgreiem build und schägt bei fehlgeschlagenen Test Alarm
* das Team fixt den Fehler schnellstmöglich
* ....


*Verantwortungsbereich des Teams*

* lade keinen Mist hoch: keinen nicht funktionierenden, ungetesteten Code
* geh erst heim wenn der build fehlerfrei durchgelaufen ist
* finde als Team deine eigenen Policies ehe sie von oben angeordnet werden
* ....


*fortlaufendes Testen und Entwickeln*

* beständiges Entwickeln ist eng mit ständiger Codeintegration verbunden und erwirkt dass deine Software die automatisierte Tests erfolgreich passiert
* gib *jeden* guten Build an deine Kunden weiter
* beständiges Integrieren und laufendes Testen des neuen Codes reduziert nicht nur Fehler, sondern führt auch schnell zu einsetzbarer Software
* wenn du alle Ratschläge beherzigst bist du in der Lage schnell deine Business-Anwendungen und Benutzerwünsche zu adaptieren. Das wiederum bedeutet eine viel bessere Zusammenarbeit zwischen Entwickler und Kunde, User. All das führt deinen Entwicklungsprozess zu einem eindeutigen Geschäftsvorteil.








