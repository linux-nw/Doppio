# Doppio

**Status:** ✅ Abgeschlossen (Demo-Projekt)

Mehrseitige Kaffee-Website mit Sorten, Rezepten, Shop-Infos und einem einfachen Bewertungssystem (HTML, CSS, PHP). Ein Konzept zum Lernen, nicht für den Live-Betrieb. Die Firma "Doppio GmbH", ihre Kontaktdaten und die Fotos sind Platzhalter.

**Name:** Doppio ist italienisch für "doppelt", wie beim doppelten Espresso.

---

## Nutzung

Auf einem Server mit PHP ausliefern, lokal zum Beispiel mit `php -S localhost:8000`, und im Browser öffnen.

Nicht auf einem öffentlichen Server betreiben: `save_review.php` schreibt Eingaben ohne Login, ohne Größenlimit und ohne Spam-Schutz in `reviews.json`.

---

## Repo-Struktur

```
index.html, About.html, Shop.html, Contact.html, rezepte.html   Seiten
stylesheet.css                                                  Gestaltung
save_review.php, reviews.json                                   Bewertungen
images/                                                         eigene oder KI-generierte Bilder
```

---

## Datenschutz

Keine Datenbank und keine Konten. Bewertungen landen unverschlüsselt in `reviews.json` auf dem Server. Deshalb nur lokal verwenden.

---

## Lizenz

[MIT](LICENSE)
