# Automatischer Zugzielanzeigengenerator + Zeitanzeigetafel
Web-App zum automatischen Generieren von Zugzielanzeigern . und Uhrzeit.
<img src="https://raw.githubusercontent.com/da-ssl/Zugzielanzeigengenerator/main/img/preview.png" alt="Vorschau des Generators" width="545"/>
<img src="https://github.com/Issy-Meow/Automatischer-Zugzielanzeigengenerator/blob/main/img/Zeitanzeiger.png" alt="Vorschau des Generators" width="545"/>
## Features:
Der automatische Zugzielanzeigengenerator kann einen S-Bahn-Anzeiger simulieren, wie er unter anderem auf der S-Bahn München verbaut ist. 
Die Züge werden automatisch abgerufen - nur Stationsnummer eingeben und ab die Post.
Zeitanzeige wie am Bahnhof
- **IBNR in die index.html eintragen**: Die Zugdaten werden automatisch abgerufen
- # NEU
- **Automatisches Generieren mithilfe der IBNR:** Der Generator wurde so modifiziert, das die IBNR automatisch angezeigt bzw. generiert wird.
Das heißt IBNR eingetragen (<a href="[www.michaeldittrich.de/ibnr/online.php]">IBNR Verzeichnis</a>) und schon wird automatisch die Anzeige des zb. Ahauser Bahnhofs (IBNR 8000437) erscheinen.
Das ermöglicht vielseitige Einsatzmöglichkeiten für den atomatischen Generator, z. B. zum einbinden in (<a href="https://github.com/bastilimbach/docker-MagicMirror">MagicMirror2</a> als Info-Anzeiger.

Configuration:
Öffne die Index.html zum bearbeiten
Suche die Zeile:
```bash
 value="8003529"
Ersetze 8003529 mit deiner IBNR
Vollständige Zeile: <input type="text" id="ibIBNR" value="8003529"> //Ersetze den value Wert durch deine "IBNR"
SPEICHERN - Fertig
