# Casus 2: het vergunningenloket

Het loket kreeg in november 30 aanvragen binnen: terrassen, evenementen, bomen, een oliebollenkraam en meer. Een op de drie is onvolledig, heeft het verkeerde vakje aangekruist of is helemaal geen aanvraag. Een medewerker leest ze nu één voor één en zoekt in de regels wat erbij hoort. Jij bouwt de werkvoorraad van die medewerker: welke aanvraag vraagt vandaag aandacht en wat is het antwoord?

Je bouwt in drie niveaus. Begin bij niveau 1 en ga pas verder als dat werkt. Niveau 3 is voor wie snel gaat.

## Wat er in deze map staat

- `aanvragen.json`: 30 aanvragen. Per aanvraag het nummer, de datum van ontvangst, het onderwerp, wat de aanvrager op het formulier aankruiste en de tekst van de mail.
- `regels.txt`: de loketregels, twaalf artikelen op één A4.

Alles is verzonnen, ook de regels. Het zijn niet de echte regels van een gemeente.

## Niveau 1: wat voor aanvraag is het?

Typ in het venster van Claude bijvoorbeeld:

Lees de aanvragen in aanvragen.json en de regels in regels.txt. Bouw een webpagina voor een loketmedewerker. Laat per aanvraag zien wat voor aanvraag het echt is. Laat ook zien of hij compleet is en of hij aan de regels voldoet. Noem bij elk oordeel het artikel. Neem donderdag 26 november 2026 als vandaag.

Claude leest de aanvragen zelf en zet de oordelen in een bestand dat de app leest.

## Niveau 2: de werkvoorraad

Doel: aan het eind ziet de medewerker welke aanvragen vandaag aandacht nodig hebben en ligt voor elke aanvraag het antwoord klaar.

Vraag bijvoorbeeld:

- Laat per aanvraag zien welke termijn loopt en kleur rood wat vandaag aandacht nodig heeft.
- Maak per aanvraag een conceptbrief: een bevestiging, een verzoek om aan te vullen, een afwijzing met het artikel of een doorverwijzing. Zet er een knop bij om de brief te kopiëren.
- Geef elke aanvraag een status, zoals nieuw, wacht op aanvrager of besluit klaar. De status moet bewaard blijven als ik de pagina opnieuw laad.

## Niveau 3: het aanvraagformulier

Doel: aan het eind vult een inwoner een aanvraag in en ziet meteen wat er ontbreekt of niet mag. De regels staan daarvoor als code in de app, dus het formulier werkt zonder AI.

Vraag bijvoorbeeld:

- Bouw een aanvraagformulier voor inwoners dat tijdens het invullen controleert of de aanvraag compleet is en aan de regels voldoet. Zet de regels uit regels.txt daarvoor in de code.
- Haal de 30 aanvragen door het formulier en vergelijk de uitkomst met de oordelen van niveau 1. Waar verschillen ze en wie heeft gelijk?
- Maak schuifjes voor de regels, zoals de maximale diepte van een terras. Wat verandert er als je die op 4 meter zet?

## Goed om te weten

- Controleer zelf een paar oordelen in `regels.txt`: klopt wat de tool zegt?
- Een paar aanvragen zijn met opzet lastig.
- Vraag één klein ding tegelijk, dan zie je elke paar minuten resultaat.
- Snap je niet wat Claude doet, vraag het dan: wat heb je net veranderd en waarom?
