# Opdracht: de dronken student

Een dronken student (die natuurlijk geen natuurkunde studeert, want die liggen altijd keurig vroeg in bed) neemt elke seconde een stap. De grootte van de stap is steeds hetzelfde ($$R = 1$$), maar de richting waarin die stap genomen wordt is volledig willekeurig. Kies bij elke stap in de tijd een random hoek $$\alpha$$ en bepaalt vervolgens de nieuwe $$x$$-positie en $$y$$-positie. Hieronder zie je de student als blauwe stip en daarbij het gevolgde pad. Dit staat bekend als een *random walk*.

![](AnimationRandomWalk.gif)

Als twee studenten dronken zijn en ze elkaar uit het oog verliezen wordt het
erg onwaarschijnlijk dat ze elkaar nog terugvinden. Probeer de volgende
animatie na te maken waarin je de beide studenten ziet lopen. Geef op het
scherm ook aan hoe lang de gebruiker van je programma nog moet wachten tot het
programma afgelopen is.

![](AnimationRandomWalkDouble.gif)

Schrijf een functie `student()` in een bestand **student.py** waarin de stip geanimeerd wordt zoals hierboven beschreven.

Probeer ook eens of je (met en en papier) iets kan zeggen over de gemiddelde
afstand die de studenten van elkaar verwijderd zijn als functie van het aantal
stappen dat ze nemen.

Zorg dat alle code voor de animatie in diezelfde functie `student()` staat.

Filmpje opslaan? Probeer een tool als [GifGrabber](http://www.gifgrabber.com)
te gebruiken om een animated gif te maken. Die kan je in een webbrowser
bekijken.
