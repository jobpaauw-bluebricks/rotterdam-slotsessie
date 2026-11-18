# Casus 3: meldingen in de wijk

Bewoners deden dit jaar ruim 600 meldingen over de openbare ruimte: zwerfafval, kapotte lantaarnpalen, losse tegels en meer. Elke melding wordt afgehandeld, maar niemand kijkt naar het geheel. Jij bouwt een wijkmonitor voor de wijkmanager: waar gaat het steeds weer mis en wie pakt het op?

Je bouwt in drie niveaus. Begin bij niveau 1 en ga pas verder als dat werkt. Niveau 3 is voor wie snel gaat.

## Wat er in deze map staat

- `meldingen.csv`: 605 meldingen van 1 januari tot en met 31 oktober 2026 uit tien Rotterdamse gebieden. Per melding de datum, de tijd, de wijk, de straat, de categorie, de tekst van de melder, hoe de melding binnenkwam, de status, de datum van afhandeling en de plek op de kaart.

De gebieden bestaan echt. De straten en de meldingen zijn verzonnen.

## Niveau 1: wat speelt er?

Typ in het venster van Claude bijvoorbeeld:

Lees meldingen.csv. Bouw een dashboard voor een wijkmanager met het aantal meldingen per categorie, per maand en per wijk. Zoek daarna naar opvallende patronen en zet de drie opvallendste bovenaan, met uitleg.

Claude schrijft code die de meldingen telt, dus de app rekent de cijfers zelf uit.

## Niveau 2: acties met een eigenaar

Doel: aan het eind ziet de wijkmanager waar het structureel misgaat en heeft elk probleem een actie met een eigenaar.

Vraag bijvoorbeeld:

- Zet de meldingen op een kaart, met een filter op categorie.
- Zoek plekken waar dezelfde melding steeds terugkomt.
- Laat me bij een probleem een actie vastleggen met een eigenaar en een status. Die moeten bewaard blijven als ik de pagina opnieuw laad.

## Niveau 3: het meldformulier

Doel: aan het eind doet een bewoner een melding en stelt het formulier een categorie voor. Is hetzelfde al gemeld, dan zegt het formulier dat. De app gebruikt daarvoor geen AI: Claude haalt de trefwoorden per categorie uit de 605 meldingen en zet ze in de code.

Vraag bijvoorbeeld:

- Bouw een meldformulier voor bewoners dat een categorie voorstelt op basis van trefwoorden uit de meldingen en waarschuwt als dezelfde melding er al is.
- Test het voorstel op alle 605 meldingen: hoe vaak klopt het? En welke meldingen in Overig horen eigenlijk ergens anders?
- Laat de app elke maandag een kort bericht voor de wijkmanager maken: wat viel vorige week op en wat kun je de komende weken verwachten?

## Goed om te weten

- In de data zitten een paar patronen verstopt. Hoeveel vind jij er?
- Vraag Claude bij elk patroon om de cijfers erachter, dan controleer je zelf of het klopt.
- Wil je een kaart, vraag dan om kaarttegels van CARTO. De gewone kaart van OpenStreetMap laadt hier niet.
- Vraag één klein ding tegelijk, dan zie je elke paar minuten resultaat.
- Snap je niet wat Claude doet, vraag het dan: wat heb je net veranderd en waarom?
