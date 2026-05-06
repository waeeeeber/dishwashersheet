# Varino Produktbilder — manuell hochladen

Diese Bilder gehören **nicht** ins Theme-Zip (zu groß für GitHub <50 MB Limit). Sie sollen in Shopify direkt als Produkt- bzw. Files-Assets hochgeladen werden.

## Upload-Pfad in Shopify

**Shopify Admin → Inhalt → Dateien → "Datei hochladen"**

Lade alle Dateien aus diesem Ordner hoch. Anschließend stehen sie unter `shopify://shop_images/<dateiname>` zur Verfügung und können in jedem `image_picker`-Feld des Theme-Editors ausgewählt werden.

## Verwendung pro Datei

| Datei | Wofür |
|---|---|
| `varino-logo-alt.png` | Optional: Sekundäres Logo (Theme-Einstellungen → Logo → Logo) — kann das Asset-Fallback überschreiben |
| `varino-product-front.png` | **Produkt-Hauptbild** (Produkt anlegen: "Varino Spülmaschinen Blätter") |
| `varino-product-front-2.png` | Produkt — zweite Variante Frontansicht |
| `varino-product-angle.png` | Produkt — 30° Winkelansicht |
| `varino-sheet-fingers.png` | Produkt — Detail: Streifen zwischen Fingern (zeigt Halbierung) |
| `varino-stack.png` | Produkt — gestapelte Boxen (Lifestyle) |
| `varino-lifestyle-kitchen-2.png` | Produkt — alternative Küchen-Lifestyle |
| `varino-dishwasher-clean.png` | Produkt — saubere Spülmaschine (Result-Shot) |

## Im Theme bereits eingebaut (Asset-Pfad — KEIN Upload nötig)

Diese liegen im Theme unter `assets/` und werden direkt aus dem Theme geladen:

- `varino-logo.png` — Header-Logo (Fallback)
- `varino-lifestyle-kitchen.png` — Homepage-Hero-Background
- `varino-flatlay.png` — Story-Sektion
- `varino-sheet-dissolve.png` — Video-Poster
- `varino-video-dissolve.mp4` — Homepage-Hintergrundvideo
- `varino-video-kitchen.mp4` — Reserve

## Produkt anlegen

1. **Produkte → Produkt hinzufügen**
2. Titel: `Varino Spülmaschinen Blätter`
3. Handle (URL): `varino-spuelmaschinen-blaetter` (so wie in `index.json` und CTAs verlinkt)
4. Beschreibung: einkopieren / formulieren rund um 30 Streifen / 60 Waschgänge
5. Bilder: aus den Files oben einfügen (Front zuerst, dann Angle, Detail, Lifestyle …)
6. **Theme-Vorlage:** rechts unter "Theme-Vorlage" → **`varino`** auswählen
7. Speichern.
