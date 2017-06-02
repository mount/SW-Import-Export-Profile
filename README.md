# Mount Import/Export Profile für Shopware

Diese Import/Export Profile für Shopware 5* sind für einen möglichst unkomplizierten CSV-Import konzipiert. Für jedes `.json`-Profil gibt es eine Dokumentation mit Erklärungen zu jedem Feld, sowie ein leicht nachvollziehbares `.csv`-Beispiel. 


## Workflow

*Die Profile bauen aufeinander auf, können aber auch unabhängig voneinander genutzt werden.*

1. Zuerst werden mit dem Profil [`mount_article_import`](../../blob/master/mount_article_import) *einfache Artikel*, bzw. mit dem Profil [`mount_variant_article_import`](../../blob/master/mount_variant_article_import) *Variantenartikel* angelegt.
2. Dann werden mit dem Profil [`mount_image_import`](../../blob/master/mount_image_import) Bilder in Shopware geladen und den Artikeln zugewiesen.
3. Zuletzt werden mit dem Profil [`mount_pickware_erp_article_stocks`](../../blob/master/mount_pickware_erp_article_stocks) die Lagerbestände der Artikel importiert. *__Achtung__: Nur mit *Shopware ERP by Pickware* verwendbar. Ohne Pickware können nur Schritt 1 – 2 ausgeführt werden.*


## Beispiel
Nach erfolgreichem Import der Beispieldateien wurden 2 neue Artikel in Shopware angelegt:

- Der einfache Artikel `„EarPods mit Lightning Connector“ (C-123-456)`:

![](https://dl.dropboxusercontent.com/s/jlnmvqdi46g211p/example-earpods.gif "„EarPods mit Lightning Connector“ (C-123-456)")

- Und der Variantenartikel `„iPhone 7“ (D-123-456.1)`, welcher in den Farben `Gold`, `Silber` und `Schwarz`, sowie jeweils mit `32GB` und `128GB` Speicherplatz angeboten wird:
![](https://dl.dropboxusercontent.com/s/1lbcma6i7igejel/example-iphone7.gif "„iPhone 7“ (D-123-456.1)")


***
*Getestet mit Shopware 5.2.20, 5.2.22 und Pickware 3.2.27, 3.2.28 | [Lizenz](../../blob/master/LICENSE.txt)