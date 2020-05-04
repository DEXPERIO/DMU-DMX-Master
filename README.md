# Innovationen mit AR - Erlebniswelt Meeresbiologie
<b>Unterwasserwelten im Deutschen Museum erforschen mit innovativen AR Erlebnissen.</b><br>
Ein Video zur Anwendung steht bereit unter der folgenden Adresse: https://bit.ly/ar-dmu-dexperio

## Projektüberblick
<b>Diese AR-Anwendung ist entstanden im Verbundprojekt museum4punkt0 – Digitale Strategien für das Museum der Zukunft, Teilprojekt [Teilprojektname].</b> Weitere Informationen: www.museum4punkt0.de.</b>

Die AR Erlebniswelt wurde für eine Austellungsinsel im Deutschen Museum im Bereich der Meeresbiologie-Ausstellung konzipiert, bei der das Tauchbot JAGO im Vordergrund steht. Die Anwendung ist für die Verwendung im Museum gedacht, ist aber auch außerhalb des Museumskontextes erlebbar. Weitere Hinweise hierzu finden sich in der Anwendung.  

Das Projekt verfolgt das Ziel, verschiedene AR Erlebnisformen in einem Anwendungskontext erlebbar zu machen. Details zu den einzelnen Teilanwendungen finden sich untenstehend.

Vielen Dank an dieser Stelle zur Bereitstellung des JAGO 3D Modells durch das GEOMAR Helmholtz-Zentrum für Ozeanforschung Kiel.
https://www.geomar.de/zentrum/einrichtungen/tlz/jago/uebersicht/

## Teilprojekte
<b>Die Gesamtanwendung wurde für die Veröffentlichung in diesem Repository in vier Teilprojekte zerlegt.</b><br>
Die technischen Hinweise zur jeweiligen Anwendung finden sich in den entsprechenden Projektverzeichnissen.

### Abtauchen mit JAGO
<b>AR-Erlebnistyp "Erweiterte Visualisierung/Präsentation" -> AR-Stage Experience</b></br>
Ran an's Steuer - Hier lernst Du mit der JAGO Ab- und Aufzutauchen.

[DMU-DMX-Abtauchen](https://github.com/DEXPERIO/DMU-DMX-Master/tree/master/DMU-DMX-Abtauchen)

### JAGO erkunden
<b>AR-Erlebnistyp: "Exploration im Raum"-> AR Portal Experience</b></br>
Hast Du Lust, das JAGO Tauchboot von innen zu erkunden? Steig einfach ein!

<b>SZENARIO:</b> In diesem Teil der Anwendung erhalten die Besucher eine 3D Präsentation des
Unterwasserfahrzeuges JAGO auf der Ausstellungsfläche, zusammen mit wissenswerten Fakten in Form
einer interaktiven, multimedialen Präsentation.

<b>INTERAKTION:</b> Die Besucher haben über ein bereitgestelltes Tablet die Möglichkeit, das
Unterwasserboot JAGO in der Mitte der Ausstellungsfläche zu platzieren und sich über verschiedene 3D
Ansichten zusammen mit multimedialen Visualisierungslementen (Bildern, Video, Text) zu informieren.
Informationen wählt er über Hotspots am 3D Objekt aus oder über Navigationsbuttons auf dem Tablet.

<b>MEHRWERTE:</b> Die Besucher können das derzeit gar nicht als reales Objekt ausgestellte Exponat auf einer
virtuellen AR Bühne erkunden, die inmitten des Exponates entsteht. Neben verschiedenen
Visualisierungsmöglichkeiten von JAGO in 3D und der Erklärung des Objektes selbst entsteht für das
Museum die Möglichkeit, das Exponat um eine Vielzahl von Zusatzinformationen und
Visualisierungsformen zu bereichern. Im Rahmen des museum4punkt0 Projektes können außerdem
verschiedene Optionen zur Generierung von 3D Daten verglichen werden: von photogrammetrischen
Verfahren basierend auf einem Miniaturmodell, über die manuelle Nachmodellierung bis hin zur
Optimierung/Konvertierung von ursprünglichen 3D Konstruktionsdaten. Siehe hierzu unten den Punkt
Anmerkungen.

<b>TECHNIK:</b> Das AR Tracking für die Erkennung der Präsentationsfläche im Exponat kann über Marker-
oder Ground-Plane Erkennung realisiert werden. In der umgesetzten Version kommt ein speziell für das Projekt angefertigter Marker (Plakat in der Größe 50 x 70 cm) zum Einsatz.

[DMU-DMX-Erkunden](https://github.com/DEXPERIO/DMU-DMX-Master/tree/master/DMU-DMX-Erkunden)

### Die Meereswelt begreifen
<b>AR-Erlebnistyp "Greifbare Objektexploration" -> AR-Cube Experience</b></br>
Erlebe verschiedene Meeresobjekte hautnah. Greif einfach zu!<br>

<b>SZENARIO:</b> In diesem Teil der Anwendung erhalten die Besucher die Möglichkeit, die hinter Glaszylindern
verborgenen Ausstellungsobjekte mittels AR Technologien im Wortsinne zu "begreifen".

<b>INTERAKTION:</b> Die Besucher verwenden hierzu neben einem Tablet einen AR-Cube der als AR Marker
fungiert und auf den das gewählte Objekt mittels AR projeziert wird. Der Cube hat in etwa die Größe
eines Rubik-Cube Würfels und kann somit gut in der Hand gehalten und bewegt werden. Dadurch ergibt
sich ein "Mixed-Reality" Erlebnis, welches einen intensiven Erlebniseindruck aus der Kombination des
haptischen und visuellen Effekts ermöglicht.

<b>MEHRWERTE:</b> Der Besucher kann die sonst hinter Glas verborgenen Objekte im Wortsinne "begreifen"
und erhält ein intensiveren Erlebniseindruck mit haptischen, visuellen und zusätzlichen informativen
Elementen. Dem Museum werden Möglichkeiten an die Hand gegeben, zusätzliche Fakten und
Erlebnisformate zu bestehenden Exponaten anzubieten und im Rahmen des museum4punkt0
Teilprojektes die Akzeptanz einer neuen 3D Visualisierungsform auszutesten.

<b>TECHNIK:</b> Die Funktionalität basiert auf klassischer AR-Markererkennung, angewandt auf ein
geometrisches Objekt, dem AR Cube. Für die Realisierung kam als Technologie die MERGE Cube Plattform
zum Einsatz (https://mergevr.com/cube?cr=2735), die entsprechende Hard- und Software bereitstellt. Für

[DMU-DMX-Begreifen](https://github.com/DEXPERIO/DMU-DMX-Master/tree/master/DMU-DMX-Begreifen)

### Gehe auf Beutefang
<b>AR-ERlebnistyp "Gamification im AUsstelungsbereich" -> AR-Arena Experience</b></br>
Gehe auf Beutefang! Sammle Meeresobjekte auf einer Actionfahrt mit der JAGO.

[DMU-DMX-Beutefang](https://github.com/DEXPERIO/DMU-DMX-Master/tree/master/DMU-DMX-Beutefang)

