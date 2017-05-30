

# Mount: Shopware Bilder Import


>**Wichtig:** Beim Import ist nur das Hinzufügen von Bilder zu Artikeln möglich. Ein Entfernen ist über einen Import nicht möglich.


| Feldname     | Beschreibung    | Gültige Werte  | Beispiel  | Besonderheiten |
| :---: | --- | --- | :---: | --- |
| `ordernumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `A.123-456` | Zur Identifizierung des Artikels, Artikelnummer vom Hauptartikel |
| `image` | Link zum Bild des Artikels | HTTP-Link | `http://example.com/pfad/zum/bild.jpg` | |
| `main` | Vorschaubild (ja/nein) | boolean<br>[(1 oder 2)](https://twitter.com/patricklnz/status/867448846808477696) | `0` | 1 = ist Vorschaubild, 2 = ist nicht Vorschaubild |
| `position` | Position auf der Artikeldetailseite | numerisch | `2` | Bild mit kleinsten Wert steht an erster Stelle |
| `relations` | Zuordnung für Variantenartikel | Text | <code>{Farbe:Rot&#124;Größe:XL}</code> | Angabe immer in Form von {Gruppe:Option} |
| `thumbnail` | Thumbnails automatisch erstellen? | boolean | `1` | 0 = nein (Thumbnails müssen später manuell erstellt werden), 1 = ja |