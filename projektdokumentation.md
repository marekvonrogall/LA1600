# Projekt-Dokumentation

Gruppenname: Mango

Gruppenmitglieder: von Rogall, Atputharasa, Greub und Mitrovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 9.5.23      | 0.0.1   | Dokumentation angefangen und Schritte 1.1, 1.2, 1.4 ausgefüllt. |
| 16.5.23      | 0.0.2    |     Erweiterung der Dokumentation und Realisieren begonnen                           |
| 23.5.23      | 1.0.0   |    Header mit Suchleiste erstellt, Startseite erstellt                                                          |
| 30.5.23      | 1.0.1   |    Produktseite begonnen, Startseite weiter verbessert                                                          |
| 06.6.23      | 1.0.2   |    Produkt, About us und Contact us-Seiten erweitert und verbessert                                                         |

## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt möchten wir eine Webseite erstellen, die ansprechend und einfach zu bedienen ist und unsere Clothing Brand darstellt. Wir möchten durch die Verwendung von CSS das Design und die Benutzerfreundlichkeit unserer Webseite verbessern und gleichzeitig unser Verständnis für die Funktionsweise von CSS erweitern. Um zukünftig ästhetisch ansprechende und technisch einwandfreie Webseiten zu erstellen, ist es unser Ziel, unsere Fähigkeiten in den Bereichen Webdesign zu verbessern.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ----- | ------- | ----------- |------------------------------------|
| 1    |   muss              |    Qualität  | Als ein User möchte ich eine coole Startseite haben, damit die Seite interessant aussieht und mich so motiviert ein Produkt auch zu kaufen |
| 2  |    muss             |   funktional   |     Als User möchte ich ein Suchfenster zur Verfügung haben, damit ich Produkte schneller und einfacher finden kann.                               |
|3|muss|funktional|Als User möchte ich ein Filter haben, damit ich ein Vorschau zu den Produkten habe und diese schneller finde.|
|4|muss|Qualität|Als User möchte ich dass die Webseite für den Gebrauch am Telefon optimiert ist, damit sich ein Benutzer am Handy besser zurecht finden. |
|5|muss|funktional|Als User möchte ich die Kontankangaben des Betreibers sehen, damit ich diesen kontaktieren kann. |
|6|muss|Qualität|Als User möchte ich die neuesten Produkte direkt sehen, damit ich direkt auf dem neuesten Stand bin. |
|7|muss|funktional|Als User möchte ich eine Seite mit allen Produkten haben, damit ich alle Produkte direkt sehen kann.|


✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |  Browser geöffnet            | Webseite wird geöffnet        |   Startseite wird angezeigt                |
| 1.2  |  Browser  geöffnet           | Webseite wird geöffnet        |   Startseite mit Bild und Text wird angezeigt                |
| 1.3  |  Browser geöffnet            | Webseite wird geöffnet        |   Header wird mit Logo angezeigt                |
| 1.4  |  Browser geöffnet            | Webseite wird geöffnet        |   Header wird mit Logo und Buttons angezeigt                |
| 1.5  |  Browser geöffnet            | Webseite wird geöffnet        |   Header wird mit Logo und allen Symbolen angezeigt                |
| 2.1 |  Startseite geöffnet            | Es wird auf die Lupe geklickt        |   Suchfenster öffnet sich                |
| 2.2 |  Suchfenster geöffnet            | Eingabe z.B. T-Shirt        |   Alle T-Shirts werden angezeigt                |
| 2.3 |  Suchfenster geöffnet, Eingabe in der Suchleiste getätigt            | Es wird auf X gedrückt        |   Inhalt in der Suchleiste wird gelöscht                |
| 2.4 |  Suchfenster geöffnet            | Eingabe z.B. H       |   Vorschläge werden angezeigt, z.B. Hose                |
| 2.5 |  Startseite geöffnet            | Es wird auf die Lupe geklickt        |  Suchfenster mit Text darin wird angezeigt                |
| 3.1 |  Startseite geöffnet            | Es wird  auf Produkte gedrückt        |   Produktseite wird geöffnet                |
| 3.2 |  Produktseite geöffnet            | Es wird auf einen Filter geklickt        |   Resultate werden korrekt gefiltert                |
| 3.3 |  Produktseite geöffnet, Filter angewendet            | Benutzer klickt auf X        |   Filter werden zurückgesetzt                |
| 4.1 |  (Am Handy) Browser geöffnet        | Webseite wird geöffnet                    | Es soll ein für das Handy optimierte Design angezeigt werden |
| 5.1 |  Startseite geöffnet            | Es wird auf About Us geklickt        |   Es soll heruntergescrollt und die _About Us_ Sektion angezeigt werden                |
| 6.1 |  Startseite geöffnet            | Benutzer scrollt nach unten        |   Neue Produkte Sektion soll zusehen sein                |
| 6.2 |  Startseite geöffnet, Neue Produkte sichtbar            | Es wird auf den rechten Pfeil gedrückt        |   Es werden mehr neue Produkte angezeigt                |
| 7.1 |  Startseite geöffnet            | Es wird auf Produkte geklickt        |   Seite mit den Produkten soll geöffnet werden                |
| 7.2 |  Startseite geöffnet            | Es wird auf Produkte geklickt        |   Es sollen alle Produkte angezeigt werden                |
| 7.3 |  Produktseite geöffnet            | Benutzer fährt über das Produktbild        |   Entsprechendes Bild soll sich drehen                |
| 7.4 |  Produktseite geöffnet            | Benutzer scrollt nach unten        |  Unter den Produktbildern soll der Name des Produkts angezeigt werden                |
| 7.5 |  Produktseite geöffnet            | Benutzer scrollt nach unten        |  Unter den Produktbildern soll der Preis des Produkts angezeigt werden                |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/110892641/237025887-10e60e74-c686-4843-82c1-13005d733d05.png)
![image](https://user-images.githubusercontent.com/110892641/237029318-e6b060f0-d10d-4650-a084-bd4031074130.png)




## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   23.5    |  von Rogall         |  Bild wird auf der Startseite angezeigt            |      30         |
| 1.B  |   23.5    |  von Rogall         |  Auf dem  Bild soll ein Text und ein Button angezeigt werden            |      45         |
| 1.C  |   23.5    |  von Rogall         |  Es soll einen Header geben, auf dem das Logo ganz links angezeigt werden soll            |     40          |
| 1.D  |   23.5    |  von Rogall         |  Auf dem Header soll ausserdem noch ein Home, Contact Us und Products Button vorhanden sein           |     30          |
| 1.E  |   23.5    |  von Rogall         |  Der Header soll ausserdem noch ein Such- und Warenkorbsymbol zeigen           |    30           |
| 2.A  |   23.5    |  von Rogall         |  Benutzer soll auf das Suchsymbol klicken können um die Suche zu öffnen          |   45            |
| 2.B |   23.5    |  Mitrovic         |  Wenn auf das X bei der Suche gedrückt wird, soll die Eingabe gelöscht werden	|   45            |
| 2.C  |   23.5    |  Mitrovic         |  Wenn bei der Suche etwas eingegeben wird, sollen Vorschläge angezeigt werden          |     60          |
| 2.D  |   23.5    |  Mitrovic         |  In der Suchleiste soll ein kleiner Text angezeigt werden          |   30            |
| 3.A  |   23.5    |  Mitrovic         |  Es soll das Fenster zum Filtern geöffnet werden, wenn der Benutzer auf Produkte drückt          |   60            |
| 3.B  |   23.5    |  Atputharasa         |  Es sollen verschiede Filter erstellt werden mit Hilfe von Checkboxen          |   45            |
| 3.C  |   23.5    |  Atputharasa         |  Der Benutzer soll die Möglichkeit haben, die Filter zurückzusetzen          |   30            |
| 4.A  |   23.5    |  Atputharasa         |  Die Webseite soll auf den Gebrauch am Smartphone optimiert werden  |     60 |
| 5.A  |   23.5    |  Atputharasa         |  Ganz Unten auf der Seite sollen die Kontaktdaten angegeben werden           |  30             |
| 5.B  |    23.5   |Mitrovic        |Wenn der Benutzer auf "Contact us" klickt, öffnet sich eine neue Seite, auf der er seine Daten eingeben und uns kontaktieren kann.|45|
|5.C   |23.5       |Mitrovic        |Auf der "Contact us"-Seite sollte sich eine Infobox befinden, in der die Kontaktdaten über unser Unternehmen bereitgestellt werden.|30|
| 6.A  |   23.5    |  Atputharasa         |  Unter dem Bild sollen neue Produkte zur Schau gestellt werden            |    45           |
| 6.B  |   23.5    |  Atputharasa         |  Man soll sich bei den neuen Produkte von links nach rechts durchklicken können         |     60          |
| 7.A  |   23.5    |  Greub         |  Wenn der Benutzer auf Produkte drückt soll die Seite mit den Produkten geöffnet werden           |    45           |
| 7.B  |   23.5    |  Greub         |  Auf der Seite mit den Produkten sollen alle Produkte sichtbar sein           |    45           |
| 7.C  |   23.5    |  Greub         |  Wenn der Benutzer über das Bild fährt, soll sich das Produkt auf dem Bildschirm drehen          |   60            |
| 7.D  |   23.5    |  Greub         |  Unter den Bildern soll der Name des Produktes angezeigt werden          |   15            |
| 7.E  |   23.5    |  Greub        |  Unter den Bildern soll ausserdem noch der Preis des Produktes angezeigt werden          |   15            |
|8.A   |23.5       |Mitrovic       |Wenn der Benutzer auf "About Us" drückt öffnet sich eine neue Seite, auf der man viel über das Unternehmen erfahren kann |45|
|8.B   |23.5       |Mitrovic       |Auf der About Us Seite soll es einen Text haben wie die Clothing-Brand enstanden ist.|20|
|8.C   |23.5       |Mitrovic       |Auf der "About Us" Seite soll es einen Text haben, was die Clothing-Brand bietet. |20|


Total: 

## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig   | geplante Zeit | tatsächliche Zeit |
|------|-------|-------------|---------------|-------------------|
| 1.A  |   16.05.2023    | von Rogall    | 30   Min         |    25  Min             |
| 1.B  |   16.05.2023    | von Rogall    | 45  Min          |    30  Min             |
| 1.C  |   16.05.2023    | von Rogall    | 40 Min           |    40  Min             |
| 1.D  |   16.05.2023    | von Rogall    | 30  Min          |    15  Min             |
| 1.E  |   23.05.2023    | von Rogall    | 30 Min           |    25  Min             |
| 2.A  |   23.05.2023    | von Rogall    | 45 Min           |      50 Min            |
| 2.B  |  04.06.2023     |   Mitrovic  | 45 Min           |        35 Min          |
| 2.C  |   05.06.2023    |  Mitrovic   | 60 Min           |      50 MIn          |
| 2.D  |  16.05.2023     |  Mitrovic   | 30 Min           |       15 Min            |
| 3.A  |   06.06.2023    |   Mitrovic  | 60 Min           |      40 Min             |
| 3.B  |  06.06.2023     | Atputharasa | 45 Min         |     40 Min              |
| 3.C  |   06.06.2023    | Atputharasa | 30 Min           |   30 Min                |
| 4.A  |  16.05.2023        | Atputharasa | 60 Min            |  45 Min                |
| 5.A  |    16.05.2023      | Atputharasa | 30 Min           |    45 Min             |
|5.B   |04.06.2023|Mitrovic |45 Min |45 Min|
|5.C   |04.06.2023|Mitrovic |30 Min |30 Min |
| 6.A  |       |Atputharasa  | 45 Min           |                   |
| 6.B  |       |Atputharasa  | 60 Min           |                   |
| 7.A  |       |   Greub     | 45 Min           |                   |
| 7.B  |    30.05.2023   |    Greub    | 45 Min           |        60 Min           |
| 7.C  |    30.05.2023   |    Greub    | 60 Min           |        100 Min           |
| 7.D  |    16.05.2023   |    Greub    | 15  min          |         15 Min          |
| 7.E  |    16.05.2023   |    Greub    | 15  Min          |       20 Min            |
|8.A   |04.06.2023            |Mitrovic     |45 Min            |30 Min|
|8.B   |04.06.2023            |Mitrovic     |20 Min            |10 Min|
|8.C   |04.06.2023|Mitrovic     |20 Min         |10 Min|



## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

## 6 Auswerten


