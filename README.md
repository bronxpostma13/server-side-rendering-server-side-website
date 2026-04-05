# Server-Side Website

Ontwerp en ontwikkel een server-side website voor een opdrachtgever

De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/server-side-rendering-server-side-website/blob/main/docs/INSTRUCTIONS.md)


## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
De opdracht die ik heb gekregen is het maken van een app/site voor het bloementuin fraekendal.

zei hebben nog helemaal geen site wat betekent dat wij deze zelf moeten opbouwen inclussief data.
Wel hebben wij een grote stylesheet met wireflows aanleverd gekregen voor het design van de site.

Het doel van de site is dat mensen op de tuin afkomen en hier de spelletjes spelen om zo hun collectie van planten uit te breiden. 
Ook is er nog een nieuws pagina voor nieuws updates over het bloemenveld 

Voor mijn ontwerp keuzes ga ik groter deels van de aangeleverde styling af. 
Wel probeer ik op bepaalde plekken er iets anders van te maken als ik denk dat dit beter is.

## Gebruik
### responsive
Door het doel einde van de site/app ben ik vooral gefocusseerd op het design van ipad en telefoon view. 
Hier zijn screenshots van de collectie pagina op ipad en telefoon 

<img width="565" height="902" alt="Scherm­afbeelding 2026-04-05 om 19 43 03" src="https://github.com/user-attachments/assets/23f0651b-bae5-449d-895f-a8fd9cf33b5f" />

<img width="820" height="895" alt="Scherm­afbeelding 2026-04-05 om 19 43 26" src="https://github.com/user-attachments/assets/3968f3e7-2abc-4996-804d-78fc45b79f1b" />


### toegankelijk 
Mijn site is ook goed toegankelijk. Zo heeft de site goede kleur contraste en een goede tab structuur 

## Kenmerken
Ik heb voor deze site gebruik gemaakt van onderandere liquid, nodejs, express en een api
### interactie

Met deze dingen heb ik uiteindelijk een dynamische pagina moeten maken met een GET route 
Een dynamische pagina is dat de data die op je site wordt weergegeven uit een database wordt gehaald.  


Veel mensen uit het project groepje kozen voor de nieuws pagina om alle artikelen weer te geven 
Hierdoor heb ik zelf gekozen om de collectie pagina te maken. En hier alle gevonden bloemen te tonen.

Met het gebruik van een for loop hoef je maar een sectie te maken voor een knop naar de detail. En dan herhaald hij deze met exacte styling voor hoeveel planten er in de database staan 


<img width="565" height="892" alt="Scherm­afbeelding 2026-04-05 om 19 43 11" src="https://github.com/user-attachments/assets/9c96c68a-9cc4-48a7-9a1f-dcdab751b5a4" />

## Installatie
Stap 1. Fork en clone de repository 

Stap 2. Open de repo in je code editor 

Stap 3. Open de terminal (command + j op mac) en type daar npm instal 

Stap 4. nadat de node module is gedownload kan je met npm start de local host openen en daar je site zien (je moet hem wel in je terminal herstarten als aanpasingen in je nodejs maakt).

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
