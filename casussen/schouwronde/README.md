# Casus 1: de schouwronde

Op dinsdag 10 november liep een schouwer van de gemeente door Delfshaven en maakte 16 foto's van wat er opviel. Niemand heeft ze nog bekeken. Jij bouwt een app voor de coördinator van de buitendienst. Die ziet per foto wat er mis is en verdeelt het werk over de ploegen.

Je bouwt in drie niveaus. Begin bij niveau 1 en ga pas verder als dat werkt. Niveau 3 is voor wie snel gaat.

## Wat er in deze map staat

- `fotos/`: 16 foto's, van `schouw-01.jpg` tot en met `schouw-16.jpg`.
- `fotos.csv`: per foto de tijd, de straat en de plek op de kaart.
- `ploegen.csv`: de vijf ploegen van de buitendienst, wat ze doen en waar hun werf is.

De schouwronde, de straatnamen en de ploegen zijn verzonnen. De foto's zijn echte foto's met een vrije licentie, gemaakt op andere plekken; de makers staan in `fotos/BRONNEN.md`.

## Niveau 1: wat is er mis?

Typ in het venster van Claude bijvoorbeeld:

Bekijk de foto's in de map fotos en de lijst fotos.csv. Bouw een webpagina met een kaartje per foto: de foto, wat je ziet, een categorie en een urgentie (hoog, middel of laag). Zet de urgente foto's bovenaan.

Claude bekijkt de foto's zelf en zet de oordelen in een bestand dat de app leest.

## Niveau 2: werkbonnen voor de ploegen

Doel: aan het eind heeft elk probleem een werkbon met een ploeg en een status.

Vraag bijvoorbeeld:

- Maak van elk probleem een werkbon en stel voor welke ploeg uit ploegen.csv hem oppakt. Eén foto kan twee problemen tonen en twee foto's kunnen over hetzelfde probleem gaan.
- Geef elke werkbon een status: open, onderweg of klaar. De status moet bewaard blijven als ik de pagina opnieuw laad.
- Laat me een oordeel of een ploeg aanpassen als ik het er niet mee eens ben.

## Niveau 3: een dagroute per ploeg

Doel: aan het eind weet elke ploeg waar ze vandaag heen gaat en in welke volgorde.

Vraag bijvoorbeeld:

- Zet de werkbonnen op een kaart van de wijk, met een kleur per ploeg en de werven erbij.
- Maak per ploeg een dagroute die op de werf begint: eerst het urgente werk, daarna de rest op afstand.
- Maak van een werkbon een printversie die de ploeg kan meenemen.

## Goed om te weten

- Claude bekijkt de foto's terwijl je bouwt; de app zelf gebruikt geen AI. Voeg je later een foto toe, vraag Claude dan om die ook te bekijken.
- Twijfel je aan een oordeel? Vraag Claude waarom.
- Wil je een kaart, vraag dan om kaarttegels van CARTO. De gewone kaart van OpenStreetMap laadt hier niet.
- Vraag één klein ding tegelijk, dan zie je elke paar minuten resultaat.
- Snap je niet wat Claude doet, vraag het dan: wat heb je net veranderd en waarom?
