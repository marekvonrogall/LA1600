# Lern-Bericht
`Gruppenname`: Mango 

`Mitglieder`: Filip Mitrovic, Marek von Rogall, Manuel Greub, Agachan Atphutharasa

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Einleitung

In diesem Projekt ging es darum, mit HTML und CSS ein Mode-Onlineshop zu erstellen.

## Was haben wir gelernt?

In diesem Projekt haben wir gelernt, wie wir Bilder auf unserer Website drehen können, wenn man darüber hovert.

## Code-Erklärung

Als Erstes muss für das Bild die Klasse `rotating_image` festgelegt werden. So werden anschliessend nur Bilder mit dieser Klasse gedreht und nicht alle auf der Webseite vorhandenen Bilder. Hier wird die Breite und Höhe des Bildes auf 1000 Pixel festgelegt. Nun wird mit der CSS-Eigenschaft `transform` festgelegt, wie lang die Animation dauern soll.

Die Klasse `.rotating_image:hover` wird hier dazu verwendet, das Bild, wenn der Benutzer darüber hovert, um 180° zu drehen. Hierfür wird die CSS-Eigenschaft `transform` mit dem Wert `rotateY(-180deg)` verwendet, um das Bild um 180° an der Y-Achse zu drehen.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Drehende Kuh</title>
    <style>
        .rotating_image img {
            width: 1000px;
            height: 1000px;
            transition: transform 0.9s;
        }

        .rotating_image:hover img {
            transform: rotateY(-180deg);
        }
    </style>
</head>

<body>
    <div class="rotating_image">
        <img src="Kuh.jpg" alt="Drehendes Bild">
    </div>
</body>
</html>
```
*Dieser Code beinhaltet die oben beschriebenen Schritte um ein Bild zu drehen.*


Es ist wichtig zu erwähnen, dass die Werte für die Übergangszeit von 0,9 Sekunden und den Rotationswert von 180° beliebig angepasst werden können, um die Animation nach den eigenen Vorstellungen anzupassen.

![LB_DrehendeKuh3](https://github.com/marekvonrogall/LA1600/assets/110893394/5003f612-e105-485f-ba5d-9e369f6a151d)

*Hier sieht man, wie sich das Bild dreht.*



## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, wie man ein sich drehendes Bild auf einer Website implementieren kann.

* `Gif:` Das Gif dient zur Veranschaulichung des Codes (Beispielwebsite mit drehendem Bild).

# Reflexion zum Arbeitsprozess


👍Bei unserer Arbeit lief gut, dass wir alle sehr viel Spass an unserem Projekt hatten, weshalb wir auch gut mit unserer Website vorankamen. Wir verstanden uns sehr gut miteinander, wodurch wir am Ende eine qualitativ hochwertige Website abliefern konnten.


👎Bei unserer Arbeit lief die Planung nicht gut. Die Arbeitspakete wurden zugeteilt, jedoch hatten die Gruppenmitglieder innerhalb dieser Arbeitspakete unterschiedlich viel Arbeit zu erledigen.
Das führte dazu, dass Gruppenmitglieder ihre Arbeitspakete schon beenden konnten, während andere noch lange nicht fertig waren. 


**VBV**: Für unser nächstes Projekt nehmen wir uns vor klare Arbeitspakete zu definieren, eine gleichmässige Verteilung der Arbeit sicherzustellen und die regelmässige Kommunikation zu fördern.


