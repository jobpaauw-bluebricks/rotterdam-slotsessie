# Casus 2: het vergunningenloket

Het loket kreeg in november 30 aanvragen binnen: terrassen, evenementen, bomen, een oliebollenkraam en meer. Een medewerker leest ze nu één voor één en zoekt in de regels wat erbij hoort. Jij bouwt een tool die dat voorwerk doet. Bij elk oordeel laat de tool zien op welk artikel het rust, zodat de medewerker het kan controleren.

## Wat er in deze map staat

- `aanvragen.json`: 30 aanvragen. Per aanvraag het nummer, de datum van ontvangst, het onderwerp, wat de aanvrager op het formulier aankruiste en de tekst van de mail.
- `regels.txt`: de loketregels, twaalf artikelen op één A4.

Alles is verzonnen, ook de regels. Het zijn niet de echte regels van een gemeente.

## Wat je bouwt

Een overzicht voor de loketmedewerker. Per aanvraag zie je wat voor aanvraag het echt is. Ook zie je of hij compleet is en of hij aan de regels voldoet, met het artikel waar dat oordeel op rust.

## Zo begin je

Typ in het venster van Claude bijvoorbeeld:

Lees de aanvragen in aanvragen.json en de regels in regels.txt. Bouw een webpagina voor een loketmedewerker. Laat per aanvraag zien wat voor aanvraag het echt is. Laat ook zien of hij compleet is en of hij aan de regels voldoet. Noem bij elk oordeel het artikel. Neem donderdag 26 november 2026 als vandaag.

## Als je verder wilt

- Laat de tool per aanvraag een conceptantwoord aan de aanvrager schrijven.
- Maak een teller: hoeveel aanvragen zijn compleet, hoeveel onvolledig en hoeveel horen niet bij dit loket?
- Kleur een aanvraag rood als een termijn verlopen is.
- Zoek de aanvragen waarbij de aanvrager het verkeerde vakje aankruiste.

## Goed om te weten

- Controleer zelf een paar oordelen in `regels.txt`: klopt wat de tool zegt?
- Een paar aanvragen zijn met opzet lastig.
- Vraag één klein ding tegelijk, dan zie je elke paar minuten resultaat.
