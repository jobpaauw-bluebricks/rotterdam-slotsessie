# Casus 1: de schouwronde

Op dinsdag 10 november liep een schouwer van de gemeente door Delfshaven en maakte 16 foto's van wat er opviel. Niemand heeft ze nog bekeken. Jij bouwt een app die dat werk doet: AI bekijkt de foto's, zegt wat er mis is en hoe snel het opgelost moet worden.

## Wat er in deze map staat

- `fotos/`: 16 foto's, van `schouw-01.jpg` tot en met `schouw-16.jpg`.
- `fotos.csv`: per foto de tijd, de straat en de plek op de kaart.

De schouwronde en de straatnamen zijn verzonnen. De foto's zijn echte foto's met een vrije licentie, gemaakt op andere plekken; de makers staan in `fotos/BRONNEN.md`.

## Wat je bouwt

Een overzicht van de schouwronde. Per foto zie je wat erop staat, de categorie (bijvoorbeeld bestrating, straatverlichting, groen of zwerfafval) en de urgentie: hoog, middel of laag. Hoe het eruitziet, bepaal jij.

## Zo begin je

Typ in het venster van Claude bijvoorbeeld:

Bekijk de foto's in de map fotos en de lijst fotos.csv. Bouw een webpagina met een kaartje per foto: de foto, wat je ziet, een categorie en een urgentie (hoog, middel of laag). Zet de urgente foto's bovenaan.

## Als je verder wilt

- Zet de foto's op een kaart van de wijk.
- Laat de app per probleem een werkbon maken voor de buitendienst.
- Vraag Claude welke foto's over hetzelfde probleem gaan.
- Maak een filter op categorie of urgentie.

## Goed om te weten

- Claude bekijkt de foto's terwijl je bouwt. Voeg je later een nieuwe foto toe, vraag Claude dan om die ook te bekijken.
- Twijfel je aan een oordeel? Vraag Claude waarom.
- Wil je een kaart, vraag dan om kaarttegels van CARTO. De gewone kaart van OpenStreetMap laadt hier niet.
- Vraag één klein ding tegelijk, dan zie je elke paar minuten resultaat.
