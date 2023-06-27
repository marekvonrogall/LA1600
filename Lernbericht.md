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
*Dieser Code beinhaltet die oben beschriebenen Schritte zur Generierung un zufälligen Auswahl der Objekte.*


Es ist wichtig zu erwähnen, dass die Werte für die Übergangszeit von 0,3 Sekunden und den Rotationswert von 180° beliebig angepasst werden können, um die Animation nach den eigenen Vorstellungen anzupassen.

![LB_DrehendeKuh3](https://github.com/marekvonrogall/LA1600/assets/110893394/5003f612-e105-485f-ba5d-9e369f6a151d)

*Hier sieht man, wie sich das Bild dreht.*



## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Gif:` Das Gif dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess


👍Bei unserer Arbeit lief gut,  


👎Bei unserer Arbeit lief nicht gut, nd zweite Schritt von IPERKA (Informieren und Planen) ist uns eher weniger gelungen. 


**VBV**: Ein Verbesserungsvorschlag für uns wäre, 


