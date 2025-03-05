# Webcam-Profil Archivator

## Neue Funktionen in Version 1.5

### Verbesserungen
- Dynamische URL-Erkennung
- Unterstützung zusätzlicher Subdomains (z. B. `de.chaturbate.com`, `de.bongacams.com`)
- Ausschluss von Kategorieseiten
- Erweitertes Popup-Menü mit Einstellungen
- Verbesserte Domain-Erkennung für alle unterstützten Plattformen

### Unterstützte Plattformen
- **Chaturbate** (inkl. aller Subdomains wie `de.chaturbate.com`)
- **Stripchat** (inkl. `stripchat.global`)
- **XHamsterLive**
- **Bongacams** (inkl. aller Subdomains wie `de.bongacams.com`)

### Funktionen
- Aktivieren/Deaktivieren des Add-ons
- Einzelne Plattformen aktivieren/deaktivieren
- Benutzerdefinierte URLs hinzufügen
- Schnellsuche von Profilen auf [Archivebate](https://archivebate.com)

## Installation
1. Entpacken Sie die Erweiterungsdateien.
2. Öffnen Sie Chrome und navigieren Sie zu `chrome://extensions/`.
3. Aktivieren Sie den **Entwicklermodus**.
4. Klicken Sie auf **Unverpackte Erweiterung laden**.
5. Wählen Sie den Ordner mit der Erweiterung aus.

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
