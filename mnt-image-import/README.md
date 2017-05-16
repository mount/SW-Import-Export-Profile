

# Mount: Shopware Bilder Import


>**Wichtig:** Beim Import ist nur das Hinzufügen von Bilder zu Artikeln möglich. Ein Entfernen ist über einen Import nicht möglich.


| Feldname     | Beschreibung    | Gültige Werte  | Beispiel  | Besonderheiten |
| :---: | --- | --- | :---: | --- |
| `ordernumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `A.123-456` | Zur Identifizierung des Artikels, Artikelnummer vom Hauptartikel |
| `image` | Link zum Bild des Artikels | HTTP-Link | `http://example.com/pfad/zum/bild.jpg` | |
| `main` | Vorschaubild (ja/nein) | boolean | `0` | 0 = ist nicht Vorschaubild  , 1 = ist Vorschaubild |
| `position` | Position auf der Artikeldetailseite | numerisch | `2` | Bild mit kleinsten Wert steht an erster Stelle |
| `relations` | Zuordnung für Variantenartikel | Text | `{Farbe:Rot|Größe:XL}` | Angabe immer in Form von {Gruppe:Option} |
| `thumbnail` | Thumbnails automatisch erstellen? | boolean | `1` | 0 = nein (Thumbnails müssen später manuell erstellt werden), 1 = ja |