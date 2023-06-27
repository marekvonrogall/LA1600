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

```c#
GameObject obstical = new GameObject("Obstical");
            GameObject cube1 = GameObject.CreatePrimitive(PrimitiveType.Cube);
            GameObject cube2 = GameObject.CreatePrimitive(PrimitiveType.Cube);
            GameObject cube3 = GameObject.CreatePrimitive(PrimitiveType.Cube);

            RandN = randN.Next(0, 3);

            if (RandN == 0)
            {
                cube1.transform.localScale = new Vector3(0f, 0f, 0f);
                cube2.transform.localScale = new Vector3(4f, 4f, 4f);
                cube3.transform.localScale = new Vector3(4f, 4f, 4f);
            }
            else if (RandN == 1)
            {
                cube1.transform.localScale = new Vector3(4f, 4f, 4f);
                cube2.transform.localScale = new Vector3(0f, 0f, 0f);
                cube3.transform.localScale = new Vector3(4f, 4f, 4f);
            }
            else if (RandN == 2)
            {
                cube1.transform.localScale = new Vector3(4f, 4f, 4f);
                cube2.transform.localScale = new Vector3(4f, 4f, 4f);
                cube3.transform.localScale = new Vector3(0f, 0f, 0f);
            }
```
*Dieser Code beinhaltet die oben beschriebenen Schritte zur Generierung un zufälligen Auswahl der Objekte.*


Danach müssen die Würfel noch in die *Parents* eingefügt werden und an der richtigen Position platziert werden.
Damit die Hindernisse auch gut im Spiel aussehen, haben sie anschliessend noch ein schicke Textur erhalten.
Bezüglich der Hindernisse gibt es noch weitere Änderungen, jedoch haben diese weniger mit der Generierung, sondern mit der Bewegung zu tun.

![Bild1](Files/Gif.gif)  
*Hier sieht man nun das Ergebnis in unserem Spiel. Die Objekte nehmen eine von drei Formen an, so dass der Spieler diesen dann ausweichen kann.*



## Verifikation

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Gif:` Das Gif dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess


👍Bei unserer Arbeit lief gut,  


👎Bei unserer Arbeit lief nicht gut, nd zweite Schritt von IPERKA (Informieren und Planen) ist uns eher weniger gelungen. 


**VBV**: Ein Verbesserungsvorschlag für uns wäre, 


