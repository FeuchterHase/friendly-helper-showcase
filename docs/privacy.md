# Datenschutz und Transparenz

Dieses oeffentliche Showcase-Repository enthaelt ausschliesslich Dokumentation.

Es enthaelt nicht:

- Bot-Token
- API-Keys
- Datenbanken
- Logs
- produktive Serverkonfiguration
- interne Pfade
- Crawler-/Watchdog-Implementierung
- private Codebasis

## Daten im Bot-Kontext

Friendly-Helper arbeitet mit oeffentlich bzw. ueber Spiel-APIs verfuegbaren World-of-Warships-Daten und Discord-Serverinformationen, soweit diese fuer aktivierte Funktionen notwendig sind.

Beispiele:

- Spieler- und Schiffsdaten
- Claninformationen
- Ranglistenwerte
- Server-Stats wie Mitglieder- oder Onlinezahlen

Admin-Funktionen wie Server-Stats oder Clan-Stats werden nicht ungefragt aktiviert. Server-Admins steuern, welche Funktionen genutzt werden.

## Keine Datenbank-Dumps

Dieses Repository enthaelt keine produktiven Datenbankdateien.

Ausgeschlossen sind insbesondere:

- SQLite-Dateien
- Logs
- Cache-Dateien
- lokale Runtime-Daten

## Private Profile

Wenn ein Spielerprofil im Spiel privat ist, soll diese Einstellung respektiert werden. Die Webplattform und der Bot behandeln private oder nicht verfuegbare Daten gesondert.

## Oeffentliche Projektpraesentation

Das Ziel dieses Repositories ist Transparenz ueber den Funktionsumfang, nicht die Offenlegung der produktiven Infrastruktur.

Die eigentliche Codebasis bleibt privat.
