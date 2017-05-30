

# Mount: Pickware Lagerbestände Import/Export


>**Wichtig:** Vor dem Import von Lagerbeständen muss die Initialisierung der Artikel im Shopware-Backend zunächst manuell angestoßen werden. [Mehr Informationen zur Initialisierung.](https://docs.google.com/document/d/1O2BHC--F_3Fmzke-MN-8ghnVJfe0pYAW_Tb9jht-Y9o/edit#heading=h.r055irix9zd2)



| Feldname     | Beschreibung    | Gültige Werte  | Beispiel  | Besonderheiten |
| :---: | --- | --- | :---: | --- |
| `ordernumber` | Artikelnummer | [Artikelnummer](http://community.shopware.com/Artikelnummern-in-Shopware_detail_642.html) | `C123-456` | Zur Identifizierung des Artikels |
| `warehouse` | Lagerkürzel | Text | `HL` | Abkürzung des jeweiligen Lagers, Lager muss bereits in Shopware angelegt sein |
| `binLocation` | Lagerplatz | Text | `A-1-1` | [Dokumentation zur Lagerplatzpflege](https://docs.google.com/document/d/1O2BHC--F_3Fmzke-MN-8ghnVJfe0pYAW_Tb9jht-Y9o/edit#heading=h.qf6w0omvh2jc) |
| `physicalStock` | physischer Lagerbestand | numerisch | `86` | |
| `availableStock` | verfügbarer Lagerbestand | numerisch | `86` | |
| `purchasePrice` | letzter Einkaufspreis | numerisch | `15.00` | |