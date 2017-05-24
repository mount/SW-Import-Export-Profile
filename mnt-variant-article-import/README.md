

# Mount: Shopware Variantenartikel Import


| Feldname     | Beschreibung    | Gültige Werte  | Beispiel  | Besonderheiten |
| :---: | --- | --- | :---: | --- |
| `ordernumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `C123-456.1` | Artikelnummer einzigartig für jeden Variantenartikel |
| `mainnumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `C123-456` | Artikelnummer des Hauptartikels, bei allen Artikelvarianten gleich. |
| `name` | Artikelbezeichnung | Text | `iPhone 7` | Bei allen Artikelvarianten gleich. Varianten-spezifische Bezeichnungen im Feld `additionalText` |
| `supplier` | Hersteller | Text | `Apple Inc.` | |
| `tax` | Steuersatz | numerisch | `19.00` | |
| `kind` | vorausgewählter Artikel | boolean | `1` | 1 = ist Vorauswahl, 0 = ist nicht Vorauswahl |
| `price_EK` | Artikelpreis | numerisch | `759.00` | Verkaufspreis |
| `active` | Im Shop anzeigen? | boolean | `1` | 0 = wird nicht angezeigt, 1 = wird angezeigt |
| `categories` | Kategorie-ID | numerisch | `94` | Kategorie muss vorher im Backend angelegt werden, Kategorie-ID wird fest von Shopware generiert |
| `configOptionName` | Steuersatz | numerisch | `19.00` | |
| `additionalText` | Zusatztext für Artikelvariante | Text | `– Schwarz, 32GB` |  wird im Frontend zusammen mit `name` angezeigt |