# Eberlando


## Was ist Eberlando
Eberlando ist eine Seite auf der ähnlich wie bei Lieferando etwas bestellt werden kann.
Allerdings ein Allzwecklieferdienst. Der wichtigere Punkt ist allerdings die Analyse und Darstellung der Userdaten.


## Aufbau
Die Standardfunktionen, wie Dinge bestellen sollen ganz normal implementiert werden. Natürlich auch mit einer Datenbank der User-Daten. Eine weitere Hauptfunktion soll sein, die Daten auszuwerten, z.B. was bestellt wird, wie häufig im Zusammenhang mit etwas anderem, zu welcher Uhrzeit, von wo aus am meisten, aber auch generelle Aufrufe der Website, und vieles mehr.

Weitere Idee, dass man auch etwas Anfragen kann, was geliefert werden soll und der Admin kann das dann annehmen oder ablehnen.

Für die Website selbst, wird vermutlich flask gebraucht um das Grundgerüst zu bauen, aber auch html.
Für die Analyse, wird aber numpy benutzt und zur Darstellung dieser auf jeden Fall matplotlib.
Für die Datenbank, wird pandas/sql genutzt


## Zeitplan/Projektaufbau

1. Grundgerüst der Seite, mit Login </br>
    1.1 Die einzelnen Unterseiten, für normale User + Admin </br>
    1.2 Aufbau, wie was bestellt werden kann </br>
2. Admin page </br>
    2.1 festlegen, welche Daten gesammelt werden sollen </br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.1 Beispieldaten erstellen </br>
    2.2 Daten sortiert anlegen </br>
    2.3 Daten darstellen </br>
3. Fehler ausbessern
4. Evtl. Zusatzfunktionen einbauen (vlt. Android App dazu)
