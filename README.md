SAMP UDF f�r AutoHotKey
=======================
Diese Sammlung von Funktionen erm�glicht es euch, auf GTA bzw. SAMP zuzugreifen um so den Chat zu manipulieren oder Daten auszulesen.
Die UDF wurde geschrieben von **Carsten S.** (**Chuck_Floyd**).

Sie darf gerne f�r jede Art von AHK-Projekt genutzt werden, solange ein Link zu dieser Repository mindestens im Quelltext bestehen bleibt (gegen mehr hat nat�rlich keiner etwas ;)).

Funktionen
----------
### SAMP-Funktionen
* isInChat() -- `Pr�ft, ob der Spieler gerade chattet oder in einem Dialog ist`
* getUsername() -- `Liest den Namen des Spielers aus`
* getChatMessage(dwMsgId) -- `Liest die Chatnachricht mit der gegebenen ID aus`
* sendChatMessage(wText) -- `Sendet eine Nachricht od. einen Befehl direkt an den Server`
* addMessageToChatWindow(wText) -- `F�gt eine Zeile in den Chat ein (nur f�r den Spieler sichtbar)`

### Fahrzeugfunktionen
* getVehicleHealth() -- `Ermittelt die HP des Fahrzeugs, in dem der Spieler sitzt`

### Standpunktbestimmung
* getCoordinates() -- `Ermittelt die aktuelle Position (Koordinaten)`
* initZonesAndCities() -- `Initialisiert eine Liste aller Standartgebiete (Voraussetzung f�r die folgenden Funktionen dieser Kategorie)`
* calculateZone(X, Y, Z) -- `Bestimmt die Zone (= Stadtteil) aus den geg. Koordinaten`
* calculateCity(X, Y, Z) -- `Bestimmt die Stadt aus den geg. Koordinaten`
* getCurrentZonecode() -- `Ermittelt die aktulle Zone in Kurzform`
* AddZone(Name, X1, Y1, Z1, X2, Y2, Z2) -- `F�gt eine Zone zum Index hinzu`
* AddCity(Name, X1, Y1, Z1, X2, Y2, Z2) -- `F�gt eine Stadt zum Index hinzu`