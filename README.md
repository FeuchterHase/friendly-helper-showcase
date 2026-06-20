# Friendly-Helper Discord-Bot

![Status](https://img.shields.io/badge/status-aktive%20Entwicklung-c5a059)
![Sprache](https://img.shields.io/badge/sprache-Deutsch-1f6feb)
![Plattform](https://img.shields.io/badge/plattform-Discord-5865F2)
![Spiel](https://img.shields.io/badge/game-World%20of%20Warships-0b7285)
![Repository](https://img.shields.io/badge/repository-Showcase-lightgrey)

**Friendly-Helper** ist ein deutschsprachiger World-of-Warships Discord-Bot fuer Clans, Communitys und Spieler.

Der Bot verbindet Discord-Slash-Commands mit der Webplattform [friendly-helpers.de](https://friendly-helpers.de). Im Fokus stehen Spielerprofile, Schiffsinfos, Clan-Stats, Rankings, Vergleiche und Server-Stats.

> Dieses Repository ist ein oeffentliches Showcase-Repository. Die produktive Codebasis, interne Infrastruktur und Betriebsdaten sind nicht Teil dieses Repositories.

**Bot einladen:** [Friendly-Helper zu Discord hinzufuegen](https://discord.com/oauth2/authorize?client_id=1385677746847486157&permissions=2952915984&integration_type=0&scope=bot+applications.commands)  
**Community-Discord:** [discord.gg/AEFeDbAEwt](https://discord.gg/AEFeDbAEwt)  
**Befehlskatalog:** [friendly-helpers.de/#bot-befehle](https://friendly-helpers.de/#bot-befehle)

## Was Friendly-Helper macht

Friendly-Helper stellt WoWS-Daten dort bereit, wo Communitys sie brauchen:

| Bereich | Beschreibung |
| --- | --- |
| Spielerprofile | Spielerwerte, Modi, Rekorde, Errungenschaften und gespielte Schiffe |
| Schiffe | Schiffsdaten, technische Werte, Vergleiche und Spielerstatistiken |
| Clans | Clanprofile, Mitglieder, Leaderboards und Clan-Wars-Informationen |
| Rankings | Spieler-, Clan- und Schiffs-Ranglisten |
| Server-Stats | Automatische Anzeige-Voice-Channels fuer Discord-Server |
| Webintegration | Discord-Ausgaben verlinken auf passende Detailseiten |

## Beispielhafte Slash-Commands

| Command | Zweck |
| --- | --- |
| [`/info <Schiff>`](https://friendly-helpers.de/#bot-befehle) | Zeigt kompakte Schiffsdaten mit Link zur Schiff-Detailseite |
| [`/vergleich <Schiff1> <Schiff2>`](https://friendly-helpers.de/#bot-befehle) | Vergleicht zwei Schiffe inklusive Webauswertung |
| [`/schiffstats <Spieler> <Schiff>`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Werte eines Spielers auf genau einem Schiff |
| [`/spielerduell <Spieler1> <Spieler2> <Modus>`](https://friendly-helpers.de/#bot-befehle) | Vergleicht zwei Spieler in einem Statistikmodus |
| [`/rekorde <Spieler>`](https://friendly-helpers.de/#bot-befehle) | Zeigt persoenliche Spielerrekorde |
| [`/clanrang <Clan> <Spieler> [Min. Gefechte]`](https://friendly-helpers.de/#bot-befehle) | Zeigt die Position eines Spielers innerhalb eines Clans |
| [`/serverstats status | aktivieren | deaktivieren | feature | kategorie`](https://friendly-helpers.de/#bot-befehle) | Verwaltet automatische Server-Stats-Channels |
| [`/notifications setup [erstellen]`](https://friendly-helpers.de/#bot-befehle) | Prueft oder erstellt Notification-Kanaele |

Eine ausfuehrlichere Uebersicht steht in [docs/commands.md](docs/commands.md).

## Webintegration

Friendly-Helper ist nicht nur ein Discord-Bot. Viele Ausgaben verweisen auf passende Webseiten:

- Spielerprofile
- Schiffseiten
- Clanprofile
- Ranglisten
- Vergleiche
- Schiffsstatistiken

Webplattform:

**https://friendly-helpers.de**

Vollstaendiger Bot-Befehlskatalog:

**https://friendly-helpers.de/#bot-befehle**

## Screenshots

Screenshots und Beispiel-Embeds koennen in `screenshots/` abgelegt werden.

Platzhalter:

| Bereich | Status |
| --- | --- |
| Spielerprofil-Command | Screenshot folgt |
| Schiffsvergleich | Screenshot folgt |
| Clan-Leaderboard | Screenshot folgt |
| Server-Stats | Screenshot folgt |

## Datenschutzfreundlicher Ansatz

Friendly-Helper ist auf sparsame Datennutzung ausgelegt:

- keine Veroeffentlichung privater Bot-Tokens
- keine oeffentlichen Datenbank-Dumps
- keine Logs in diesem Repository
- keine produktive Serverkonfiguration
- Trennung zwischen oeffentlicher Projektpraesentation und privater Codebasis

Mehr dazu: [docs/privacy.md](docs/privacy.md)

## Private Codebasis

Die produktive Codebasis ist nicht oeffentlich. Dieses Showcase enthaelt bewusst:

- keine Python-/JavaScript-/Shell-Implementierungen
- keine API-Keys
- keine Tokens
- keine Datenbanken
- keine internen Serverpfade
- keine Crawler- oder Watchdog-Implementierung

Das Repository dient ausschliesslich der transparenten Projektvorstellung.

## Roadmap-Auszug

| Thema | Status |
| --- | --- |
| Erweiterte Spielerprofile | in Arbeit |
| Clan- und Server-Stats | aktiv |
| Mehr Web-Verknuepfungen in Commands | aktiv |
| Bessere Erklaerseiten fuer Admin-Funktionen | geplant |
| Mehr Beispiel-Screenshots | geplant |

Mehr Details: [docs/roadmap.md](docs/roadmap.md)

## Invite und Kontakt

- Bot einladen: [Friendly-Helper zu Discord hinzufuegen](https://discord.com/oauth2/authorize?client_id=1385677746847486157&permissions=2952915984&integration_type=0&scope=bot+applications.commands)
- Community-Discord: [discord.gg/AEFeDbAEwt](https://discord.gg/AEFeDbAEwt)
- Webseite: [friendly-helpers.de](https://friendly-helpers.de)
- Befehle: [friendly-helpers.de/#bot-befehle](https://friendly-helpers.de/#bot-befehle)
- Projektstatus: aktive Entwicklung

## Dokumentation

- [Features](docs/features.md)
- [Commands](docs/commands.md)
- [Datenschutz](docs/privacy.md)
- [Roadmap](docs/roadmap.md)
- [Changelog](docs/changelog.md)
