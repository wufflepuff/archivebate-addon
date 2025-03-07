# Webcam-Profil Archivator

Der **Webcam-Profil Archivator** ist eine Browser-Erweiterung, die automatisch Profilseiten auf unterstützten Plattformen erkennt und eine schnelle Suche auf [Archivebate](https://archivebate.com) ermöglicht. Mit flexiblen Einstellungen und Subdomain-Support bietet die Erweiterung eine einfache Möglichkeit, Webcam-Profile zu archivieren oder wiederzufinden.

## Funktionen
- Automatische Erkennung von Profilseiten
- Unterstützung mehrerer Plattformen und Subdomains
- Aktivieren/Deaktivieren der Erweiterung per Klick
- Einzelne Plattformen aktivieren/deaktivieren
- Benutzerdefinierte URLs hinzufügen
- Schnellsuche von Profilen auf [Archivebate](https://archivebate.com)

## Unterstützte Plattformen
- **Chaturbate** (inkl. aller Subdomains wie `de.chaturbate.com`)
- **Stripchat** (inkl. `stripchat.global`)
- **XHamsterLive**
- **Bongacams** (inkl. aller Subdomains wie `de.bongacams.com`)

## Installation

### Für Chrome / Chromium-basierte Browser:
1. Entpacken Sie die Erweiterungsdateien.
2. Öffnen Sie Chrome und navigieren Sie zu `chrome://extensions/`.
3. Aktivieren Sie den **Entwicklermodus**.
4. Klicken Sie auf **Unverpackte Erweiterung laden**.
5. Wählen Sie den Ordner mit der Erweiterung aus.

### Für Firefox:
1. Laden Sie die `.xpi`-Datei der Erweiterung herunter.
2. Öffnen Sie Firefox und ziehen Sie die `.xpi`-Datei in das Browserfenster.
3. Bestätigen Sie die Installation im Dialog.
4. Alternativ: Öffnen Sie `about:addons`, klicken Sie auf das Zahnrad und wählen Sie **Add-on aus Datei installieren...**, um die `.xpi`-Datei auszuwählen.

## Bekannte Einschränkungen
- Keine Unterstützung für Kategorieseiten (z. B. `female-cams`, `couples`).
- Nur Profile mit direkten Benutzernamen-Pfaden werden unterstützt.
- Derzeit nur auf Deutsch verfügbar.

## Fehlerbehebung
Falls Probleme auftreten:
- Überprüfen Sie, ob die Plattform-Optionen aktiviert sind.
- Stellen Sie sicher, dass der Profilpfad direkt ist (z. B. `username` statt `category/username`).
- Aktualisieren Sie die Erweiterung nach Änderungen.
- Vergewissern Sie sich, dass die Website das korrekte Format hat.

## Datenschutz
Diese Erweiterung erfasst **keine persönlichen Daten**.

## Technische Hinweise
- Die Erweiterung nutzt `endsWith()` für die Domain-Erkennung zur besseren Subdomain-Unterstützung.
- Benutzerdefinierte URLs werden vollständig unterstützt.
- Alle unterstützten Seiten verwenden dieselbe Logik zur Extraktion von Benutzernamen aus URLs.
