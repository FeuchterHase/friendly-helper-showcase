# Commands

Diese Datei zeigt beispielhaft, welche Art von Slash-Commands Friendly-Helper bereitstellt.

Die Command-Namen orientieren sich am oeffentlichen Befehlskatalog auf der Webseite:

**https://friendly-helpers.de/#bot-befehle**

Bot einladen:

**https://discord.com/oauth2/authorize?client_id=1385677746847486157&permissions=2952915984&integration_type=0&scope=bot+applications.commands**

## Schiff und Schiffsdaten

| Command | Beschreibung |
| --- | --- |
| [`/info <Schiff>`](https://friendly-helpers.de/#bot-befehle) | Zeigt kompakte Schiffsdaten mit Bild, Bewaffnung, Verbrauchsmaterialien und Link zur Schiff-Detailseite |
| [`/liste [Nation] [Klasse]`](https://friendly-helpers.de/#bot-befehle) | Listet Schiffe, optional gefiltert nach Nation und Klasse |
| [`/vergleich <Schiff1> <Schiff2>`](https://friendly-helpers.de/#bot-befehle) | Vergleicht zwei Schiffe anhand technischer Werte inklusive Webauswertung |
| [`/zufallsschiff`](https://friendly-helpers.de/#bot-befehle) | Waehlt ein zufaelliges Schiff aus |
| [`/schiffstats <Spieler> <Schiff>`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Statistik eines Spielers auf genau einem Schiff |
| [`/schiffduell <Spieler1> <Spieler2> <Schiff>`](https://friendly-helpers.de/#bot-befehle) | Vergleicht dasselbe Schiff zwischen zwei Spielern |

## Spieler

| Command | Beschreibung |
| --- | --- |
| [`/mystats <Spieler> <Modus>`](https://friendly-helpers.de/#bot-befehle) | Zeigt Spielerstatistiken fuer PvP, PvE, Solo und Divisionen |
| [`/spielerduell <Spieler1> <Spieler2> <Modus>`](https://friendly-helpers.de/#bot-befehle) | Vergleicht zwei Spieler in einem Statistikmodus |
| [`/top_schaden <Spieler>`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Top 10 Schiffe eines Spielers nach hoechstem Einzelschaden |
| [`/hits liste <Spieler> [Nation] [Klasse] [Anzahl]`](https://friendly-helpers.de/#bot-befehle) | Zeigt Trefferquoten und erweiterte Schiffswerte als Liste |
| [`/meineschiffe <Spieler> [Nation]`](https://friendly-helpers.de/#bot-befehle) | Zeigt gespielte Schiffe eines Spielers inklusive letztem Gefecht |
| [`/rekorde <Spieler>`](https://friendly-helpers.de/#bot-befehle) | Zeigt persoenliche Spielerrekorde |
| [`/errungenschaften <Spieler>`](https://friendly-helpers.de/#bot-befehle) | Zeigt kompakt unterschiedliche und insgesamt erhaltene Errungenschaften |
| [`/expert player <Klasse> <Spieler>`](https://friendly-helpers.de/#bot-befehle) | Zeigt E-, Klasse-1-, Klasse-2- oder Klasse-3-Abzeichen eines Spielers |

## Clan

| Command | Beschreibung |
| --- | --- |
| [`/clanmitglieder <Clan>`](https://friendly-helpers.de/#bot-befehle) | Zeigt Clanmitglieder mit Rolle und letztem Gefecht |
| [`/leaderboard <Clan> <Sortierung> [Min. Gefechte]`](https://friendly-helpers.de/#bot-befehle) | Erstellt ein Top-10-Clanranking nach gewaehlter Sortierung |
| [`/clanrang <Clan> <Spieler> [Min. Gefechte]`](https://friendly-helpers.de/#bot-befehle) | Zeigt den persoenlichen Rang eines Spielers innerhalb eines Clans |
| [`/clanrekorde <Clan>`](https://friendly-helpers.de/#bot-befehle) | Zeigt Clanrekorde aus der Webseite als Discord-Embed |

## Web-Rankings

| Command | Beschreibung |
| --- | --- |
| [`/clanwars`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Top 5 des EU Clan-Wars Leaderboards |
| [`/spieler-rankings`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Top 5 der Spieler-Rangliste |
| [`/schiffs-meta [Tier] [Nation] [Klasse] [Min. Gefechte] [Sortierung]`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Top 5 der serverweiten Schiffs-Meta mit Filtern |
| [`/clan-rankings`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Top 5 der Clan-Rankings |

## Notification Center

| Command | Beschreibung |
| --- | --- |
| [`/notifications setup [erstellen]`](https://friendly-helpers.de/#bot-befehle) | Prueft Notification-Kanaele oder erstellt den Standardbereich |
| [`/notifications kanal <Modul> <Channel>`](https://friendly-helpers.de/#bot-befehle) | Setzt den Zielkanal pro Notification-Modul |
| [`/notifications an | aus <Modul>`](https://friendly-helpers.de/#bot-befehle) | Aktiviert oder deaktiviert einzelne Module |
| [`/notifications clan-hinzufuegen <Clan>`](https://friendly-helpers.de/#bot-befehle) | Verknuepft Clans fuer Notifications |
| [`/notifications status | liste | clans`](https://friendly-helpers.de/#bot-befehle) | Zeigt Konfiguration, Module und verknuepfte Clans |
| [`/notifications test <Modul>`](https://friendly-helpers.de/#bot-befehle) | Sendet einen Beispielpost in den gesetzten Kanal |

## Karten, Kommandanten und Sammlung

| Command | Beschreibung |
| --- | --- |
| [`/karte <Karte>`](https://friendly-helpers.de/#bot-befehle) | Zeigt Details zu einer bestimmten Karte |
| [`/karten`](https://friendly-helpers.de/#bot-befehle) | Listet vorhandene Karten |
| [`/kommandant <Name>`](https://friendly-helpers.de/#bot-befehle) | Zeigt Details zu einem bestimmten Kommandanten |
| [`/kommandanten <Nation>`](https://friendly-helpers.de/#bot-befehle) | Listet Kommandanten einer Nation |

## Server- und Clan-Stats

| Command | Beschreibung |
| --- | --- |
| [`/serverstats status | aktivieren | deaktivieren | feature | kategorie`](https://friendly-helpers.de/#bot-befehle) | Verwaltet automatische Server-Statistik-Channels |
| [`/clanserver hinzufuegen | status | entfernen | aktualisieren`](https://friendly-helpers.de/#bot-befehle) | Verknuepft WoWS-Clans mit einem Discord-Server |
| [`/clanserverstats status | aktivieren | deaktivieren | feature`](https://friendly-helpers.de/#bot-befehle) | Verwaltet automatische Clan-Statistik-Channels |

## Allgemein

| Command | Beschreibung |
| --- | --- |
| [`/help`](https://friendly-helpers.de/#bot-befehle) | Zeigt alle wichtigen Befehle und Beispiele |
| [`/aboutme`](https://friendly-helpers.de/#bot-befehle) | Zeigt eine kurze Uebersicht zum Friendly-Helper Bot |

## Weblinks

Viele Commands verlinken auf passende Detailseiten von:

- https://friendly-helpers.de
- https://friendly-helpers.de/#bot-befehle

So bleibt Discord kompakt, waehrend Detaildaten in der Webansicht verfuegbar sind.
