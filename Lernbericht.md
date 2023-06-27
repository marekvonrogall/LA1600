# Lern-Bericht
`Gruppenname`: Mango 

`Mitglieder`: Filip Mitrovic, Marek von Rogall, Manuel Greub, Agachan Atphutharasa

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Einleitung

In diesem Projekt ging es darum, mit HTML und CSS ein Mode-Onlineshop zu erstellen.

## Was haben wir gelernt?

In diesem Projekt haben wir gelernt, wie wir Bilder auf unserer Website drehen können, wenn man darüber hovert.

## Code-Erklärung


Bei der Erstellung des *Obsticles* werden *Parents* als durchsichtige Boxen verwendet, welche die *Children* enthalten. Hierfür verwenden wir ein leeres Game Object als *Parent* und drei Würfel als *Children*. 
Da unser Spiel drei Spuren besitzt, auf denen sich der Spieler bewegen kann, werden davon zwei von den Objekten eingenommen. Hierfür werden drei Schablonen erstellt und mit einem Zufalls-Generator und *System.Random* ausgewählt, wobei immer ein unsichtbarer Würfel erzeugt wird, indem seine Grösse auf 0 gesetzt wird.

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
            transition: transform 0.3s;
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


Danach müssen die Würfel noch in die *Parents* eingefügt werden und an der richtigen Position platziert werden.
Damit die Hindernisse auch gut im Spiel aussehen, haben sie anschliessend noch ein schicke Textur erhalten.
Bezüglich der Hindernisse gibt es noch weitere Änderungen, jedoch haben diese weniger mit der Generierung, sondern mit der Bewegung zu tun.

![LB_DrehendeKuh](https://github.com/marekvonrogall/LA1600/assets/110893394/53777c0d-3b83-491e-8915-bab2398aae75)

*Hier sieht man wie sich das Bild dreht.*



## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Gif:` Das Gif dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess


👍Bei unserer Arbeit lief gut,  


👎Bei unserer Arbeit lief nicht gut, nd zweite Schritt von IPERKA (Informieren und Planen) ist uns eher weniger gelungen. 


**VBV**: Ein Verbesserungsvorschlag für uns wäre, 


