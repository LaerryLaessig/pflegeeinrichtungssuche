# Pflegeeinrichtungssuche
Dies ist eine Web-Anwendung, mit der man nach verschiedenen sozialen und Pflegeeinrichtungen in einem bestimmten Umkreis suchen kann.

## Funktionen
- Standortbasierte Suche: Findet Einrichtungen basierend auf einem eingegebenen Ort und einem definierten Radius.
- Filteroptionen: Ermöglicht die Filterung nach spezifischen Einrichtungstypen wie Senioren-/Pflegeheim, Kindergarten, Behinderteneinrichtung und Tagespflege.
- Kontaktinformationen: Zeigt, falls verfügbar, grundlegende Informationen wie Adresse, Telefonnummer und E-Mail-Adresse der gefundenen Einrichtungen an.
- Anpassbare Benutzeroberfläche: Enthält einen Schalter zum Umschalten zwischen hellem und dunklem Modus.

## Technologie
Das Projekt ist ein einzelnes HTML-Dokument, das alle notwendigen Komponenten enthält:
- HTML: Struktur der Anwendung.
- CSS: Styling mit Tailwind CSS für ein modernes, responsives Design.
- JavaScript: Kernlogik, API-Aufrufe und Karteninteraktion.
- Overpass API: Dient als primäre Datenquelle, um Geodaten von OpenStreetMap abzufragen.
- Nominatim: Wird für die Geocodierung von Adressen verwendet, um die Koordinaten für die Suche zu ermitteln.

## Wie man es benutzt

Die Anwendung kann direkt in einem Webbrowser geöffnet werden.
Öffne die index.html-Datei in deinem bevorzugten Browser.
Gib deinen Standort (eine Stadt oder Adresse) und den gewünschten Umkreis ein.
Wähle die gewünschten Einrichtungstypen über die Checkboxen aus.
Klicke auf den "Suchen"-Button, um die Ergebnisse zu sehen.
