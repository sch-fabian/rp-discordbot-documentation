# Changelog

Alle bemerkenswerten Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

# Unreleased

## 3.0.0

### Added

- `!item` - Zum verwalten, anschauen und kaufen von Items
- `!cat` - Zum verwalten von Kategorien



# Released

## 2.0.1 [22.06.2020]

### Changed
- Nutzer mit nur einem Charakter können nun !login benutzen
- Für Supporter sind Konten von anderen jetzt auch über die DMs abrufbar

## 2.0.0 [21.06.2020]

### Added
- Datenbank Tabelle zum sammeln von Statistiken
- Die Anzahl der geschriebenen Nachrichten werden gezählt
- Anlegen des Users in die Statistikendatenbank wenn er auf den Server joint
- Funktion um zu überprüfen wenn die Rolle eines Users geändert wird
- `!login` - Bei mehreren Charakteren wählt man so den aktiven Charakter mit dem man handelt
- `!support` - Der Bot schreibt dir eine Nachricht um mit dem Ticketssytem zu interagieren
- `!ticket` - Ticketssystem zum erstellen und auflisten von Tickets. Supporter und höher haben die möglichkeit den Status eines Tickets zu ändern und ein Ticket sich selbst zuzuweisen
- `!stats` - Bietet Ownern die Möglichkeit Statistiken zu Usern auf dem Server aufzurufen
- `!initialize` - Befehl zum initialisieren des Bots bei einer neuen Version
- `!credits` - Zeigt die Credits zu dem Bot an, auch die Version ist einsehbar und das Trello Board mit dem aktuellen Stand und zukunftügen Feauters

### Changed
- Funktion zum prüfen der Berechtigungen geändert und passend zu den Rollen auf dem Server gemacht. Berechtigungen werden mit ändern der Rolle geändert.
- `!help` - Aussehen der Nachricht geändert, passend zu den Berechtigungen werden alle Befehle angezeigt, Text um neue Befehle erweitert
- `!konto` wurde nun mit `!chars` zusammengelegt, Aussehen der Nachricht geändert
- `!pay` - Synatx geändert. Nun muss nicht mehr angeben werden von welchem Charakter Geld gegeben wird

## 1.0.0

### Added
- `!help` - Zum Anzeigen eines Hilfetextes mit allen Keywords der Befehlen und der Syntax.
- `!clear` - Löscht die angebene Anzahl von Nachrichten aus dem Channel
- `!reg` - In Verbindung mit der Charakternamen und der DiscordID wird ein neuer Charakter für den User in die Datenbank geschrieben
- `!chars` - Listet in Verbindung mit der DiscordID alle Charaktere des Nutzers auf
- `!konto` - Zu dem jeweiligen Charakter wird der aktulle Kontostand angezeigt
- `!pay` - Man gibt von einem seiner Charaktere Geld an einen andereren Charakter
- `!hausdesgeldes` - Einem Charakter wird die angegebene Menge an Geld gutgeschrieben
- `!kill` - Mit angabe des Charakters wird dieser aus der Datenbank gelöscht
- Funktion um die Rolle einens User auszulesen um Berechtigungen auf bestimmte Befehle zu geben
