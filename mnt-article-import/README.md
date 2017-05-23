

# Mount: Shopware einfacher Artikel Import


>**Wichtig:** Dieses Profil ist zur Anlage einfacher Artikel gedacht. Für Variantenartikel siehe [`mnt-variant-article-import`](https://github.com/mount/SW-Import-Export-Profile/tree/master/mnt-variant-article-import)


| Feldname     | Beschreibung    | Gültige Werte  | Beispiel  | Besonderheiten |
| :---: | --- | --- | :---: | --- |
| `ordernumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `C123-456` |  |
| `mainnumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `C123-456` | Bei einfachem Artikel gleicher Wert wie `ordernumber` |
| `name` | Artikelbezeichnung | Text | `EarPods mit Lightning Connector` | |
| `supplier` | Hersteller | Text | `Apple Inc.` | |
| `tax` | Steuersatz | numerisch | `19.00` | |
| `price_EK` | Artikelpreis | numerisch | `35.00` | Verkaufspreis |
| `active` | Im Shop anzeigen? | boolean | `1` | 0 = wird nicht angezeigt, 1 = wird angezeigt |
| `categories` | Kategorie-ID | numerisch | `94` | Kategorie muss vorher im Backend angelegt werden, Kategorie-ID wird fest von Shopware generiert |