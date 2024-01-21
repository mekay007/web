# Fragenkatalog
1. Wie sieht ein syntaktisch richtiges HTML Dokument aus?
   ```html
   <!DOCTYPE html>
     <html>
       <head>
       ...
       </head>
       <body>
       ...
       </body>
     </html>
   ```
   Der Head hat Metafdaten von anderen Webseiten. Hiermit koennen auch externe Stylecheets oder Javascript Dokumente verlinken.<br>
   Im Body sind die Webseiten Inhalte.
3. Wann und von wem wurde der Begriff WorldWideWeb gepraegt?
   Das WWW wurde 1990 Gepraegt durch Tim Berners-Lee.
5. Was war ein Problem von Web 1.0?
   Begrenzte visuelle Ausdrucksmoeglichkeiten.
7. Wann wurde der Begriff Web 2.0 gepraegt?
   1990
9. Was versteht man unter Web 2.0?
    Umfasst verschiedene soziale und technische Entwicklung. Besonder ist hier das man jetzt nun auch dynamische Seiten und Inhalte hat.<br> Man kann mit den Webseiten interargieren und nun Inhalte selber schreiben. 
11. Was versteht man unter Web 3.0?
    Daten sollen lesbar un daher auch nutzbar fuer Maschinen und Software sein.
13. Was war die Motivation hinter Web 3.0?
    Das Web zu dezentralisieren da Unternehmen wie Meta oder Google unsere Daten besitzen und damit anstellen koennen was diese moechten.<br>
    Man Selber als User besitzt nichts im Internet. Deswegen Soll das Web 3.0 Das Prinzip der Ownership hinzufuegen.
15. Was ist eine Blockchain?
    Die Blockchain ist eine dezentrale Datenbank aus mehreren miteinander verknuepften Bloecken.<br>
    Jeder Block hatt alle Daten.
17. Was sind NFTs?
    NFT steht steht fuer Non-Fongible-Token. Dies Token sind einzigartig und koennen nur von einer Person besitzt werden.<br> Klassische Token wie Ethereum oder Bitcoin koennen zerlegt werden, ein NFT jedoch nicht. 
19. Was versteht man unter DAO?
    Ein dezentrale Organisation welche autonom arbeitet d.h. ein Stueck Code welches aufgrund von Gegebenheiten entscheidungen trifft. Diese Entscheidungen werden nur mittel Algorithmen getroffen.
21. Wofuer steht HTML?
    Hypertext Markup Language.
24. Was is HTML?
    Ist eine Textbasierte Auszeichnungssprache um Beschreibungen fuer Inhalte fuer Webseiten zu erstellen.
26. Welchen Standard unterliegt HTML?
    W3C Standard.
28. Was Passiert im Hintergrund wenn man eine HTTP Webseite besuchen will?
    Man schickt eine HTTP Request vom Client(Endbenutzer) an den Webserver.<br>
    Der Webserver mit Socket erhaelt die Requesr und schick an den Cliene eine Response.<br>
    Diese HTTP Response schickt dann fuer gewoehnlich HTML,Javascript und CSS Dateien.<br>
    Diese Dokumente wandelt der Webbrowser in ein Bild fuer den Endnutzer.
30. Was sind HTML, CSS und Javscript fuer Sprachen.
    HTML: eine Markup Language<br>
    CSS: eine Style Sheets, damit kann man Eigenschaften von Inhalten aendern (Farbe,Font,Groesse)
32. Wie lautet der aktuellste HTML Version und wann wurde diese veroeffentlicht?
    HTML5 2014
1. Was sind Frameworks und was sind Ihre Vor- und Nachteile?
   Ein Framework ist eine strukturierte und vorgefertigte Sammlung von Tools, Bibliotheken und Konventionen, die dazu dienen, die Entwicklung von Softwareanwendungen zu erleichtern.<br>
   + erleichtert die Entwicklung von Softwareanwendungen
   - Fuer kleine Applikationen ist die Aufwand der Seite im verhaeltnis gigantisch was zur unnoetigen Overhead fuehrt<br>
   - man macht sich abhaengig von von den Framework wenn dieses zestoert ist ist auch in der Regel die Applikation fuer den Eimer
34. Wie sieht die Fehlertoleranz in HTML im vergliech zu einer Programmiersprache wie c?
    Trotz syntaktischer Fehler in einem HTML Dokument wird die Seite erstellt. Dies liegt daran das ein Webbrowser einige Fehler selber korrigiert.<br>Zudem ist die Syntax von HTML ist weniger streng und teilweise auch nicht klar definiert dadurch sind Darstellungsprobleme aufgrund von Syntaxfehler verringert.
37. Wie sieht ein HTML Element aus?
    Ein Element ist zwischen Begint mit dem Start Tag und endet mit dem End Tag.
39. Gibt es leere Elemente wenn ja welche?
    Ja <br>
41. Gibt es bei den beiden Tags einen unterschied in HTML `<p>` und `<P>`?
    Ist das gleiche in HTML.
43. Koennen HTML Elemente Attrubute haben?
    JA
45. Wo und wie kann man diese Attribute aendern?
    Im Start tag in einem HTML Dokument<br>.
    Bespiel:<br>
    ```html
    <h1 style="font-color: red; background-color: blue">
    ```
    
47. Was ist der unterschied zwischen Inline und Block Elemente?
   Block Element beginnt immer mit einer neuen Zeile. Standardmaessig nimmt dies die maximale Breite des Elemnts in welches diese drin ist.<br> Enden tut es mit einem Zeilenumbruch.<br>
   Ein Inline beginnt in einer Zeile, die Breite des Elements wird anhand des benoetigten Inhalt bestimmt.
49. Welche Tags benutzt man zum erstellen eines Formulars?
    ```html
    <form>
    </form>
    ```
51. Wie binde ich eine Javascript intern und extern ein?
   test.js<br>
   ```js
   function pp(){
       let test=document.getElementById("penis");
       test.innerHTML="Penis123";
   }
   ```
    ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <script src="testj.js"></script>
</head>
<body>
<h1 id="penis">
</h1>
<script>
    let testi=document.getElementById("penis")
    testi.inneML="Penis123";
    pp();
    //Gleiche funktionalitaet einaml intern und extern
</script>
</body>
</html>
    ```
    
53. Welche Selektoren gib es alles?
54. Wie kann ich den Inhalt eines Elemnets via Javascript erweitern?
55. Welche wichtigen Event Listener gibt es und wie kann man diese hinzufuegen? Einmal mittels Dom und einmal HTML Attribut.
56. Wie Navigiere ich mich durch eine DOM?
57. Wie erzeugt, löscht und verändert man ein Element mittels DOM? Geben Sie für alle jeweil ein Besipiel.
58. Was ist das Konzept hinter AJAX und was sind fie Vor- und Nachteile?
59. Was ist HTTP und wie wird dies eingesetzt?
60. Welche HTTP Anfragemethoden gibt es?
61. Welche HTTP Status-COdes gibt es?
62. Wie ist eine HTTP URI aufgebaut?
63. Wie sichert man den Client?
64. Wie sichert man den Server?
65. Wie funktioniert der TLS Handshake zwischen Server und Cient?
# CSS Fragen?
1. Nennen Sie 3 Font-Familien?
2. Zeichnen Sie das Box-Model an und erklären Sie jedes Elemnt?
3. Was ist der unterschied zwischen content-box und bordebox?
4. Was versteht man unter Responsive Web-Design und wie kann man so ein Design realisieren?
5. Wie realisiere ich eine Mediaquery für Bildschirme die max 600px breit sind?
# HTML aufgaben:
1. Schreiben Sie einen einfachen adierer in HTML?
2. Erstellen Sie eine Tabell in HTML
# Javascript Aufgaben:

