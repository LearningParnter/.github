# LearningPartner

Willkommen im offiziellen GitHub Repository von LearningPartner! Dieses Repository dient als zentrale Anlaufstelle für alle Dokumente, Vorlagen und Konfigurationen. LearningPartner ist eine Community-/Coach-Plattform, die es Coaches ermöglicht, eigene Inhalte in Form von Videos, Papers und Blogbeiträgen zu erstellen und zu teilen.

## Übersicht

Dieses Repository enthält:
- **Dokumentationen und Handbücher:** Ausführliche Anleitungen (z. B. das Handbuch für Coaches) und interne Dokumentationen zur Verwaltung unserer Plattform.
- **Vorlagen und Richtlinien:** Templates für Issues, Pull Requests und Beitragsrichtlinien, die in allen Repositories der Organisation verwendet werden.

## Lerninhalte der Plattform

Die LearningPartner Software bietet Ihnen als Coach und Entwickler folgende Hauptfunktionen:
- **Eigene Plattform:** Coaches betreiben eine individuelle Instanz über Subdomains wie `[instance_shortcode].learningpartner.cloud` und können optional auch eine eigene Domain verbinden.
- **Content Management:** Verwaltung von Videos, Papers und Blogbeiträgen über ein intuitives Back-Office:
  - **Videos:** Erstellen, kategorisieren und hochladen mit spezifischen Einstellungen wie Titel, Beschreibung, Thumbnail, Verfügbarkeit und mehr.
  - **Papers:** Ähnlich wie Videos können auch Dokumente in vordefinierten Kategorien hochgeladen und freigeschaltet werden.
  - **Blog:** Über ein separates Modul abrufbar, können hier Inhalte verfasst und veröffentlicht werden.
- **Abonnementverwaltung:** Ein flexibles Abosystem, das Nutzern den Zugriff auf unterschiedliche Inhalte ermöglicht. Der Wechsel zwischen Abos erfolgt automatisch über unsere Software in Kombination mit der Stripe-API.
- **Zahlungsabwicklung via Stripe:** Jeder Coach richtet seinen eigenen Stripe-Account ein. Mit einem hinterlegten Secret-Key verwaltet LearningPartner die Produkte und Kunden.
- **Automatische Updates:** Die Software wird automatisch aktualisiert, wobei kurze Ausfallzeiten (bis zu 5 Minuten) möglich, aber selten und rechtzeitig angekündigt sind.
- **Ausblick:** In kommenden Versionen werden detaillierte Nutzungsstatistiken, ein Shop-Modul und ein Event-Modul integriert.
