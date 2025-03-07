---
banner: /assets/images/lisse.jpg
layout: story
published: true
title: PLDN-Werkgroep Digitaal Erfgoed
---

# PLDN-Werkgroep Digitaal Erfgoed

Dit is een Data Story in ontwikkeling.  In de PLDN werkgroep Erfgoed
hebben we een idee voor een data story beschreven.  Deze willen we de
komende weken stap voor stap gaan vullen.

## Buitenplaatsen

Joop (15 april). Query we plotten de rijksmonumenten van Lisse op een
kaart (schatting is 34) (steden landhuizen en parken, in de
beschrijving staat buitenplaats). We tonen gallery view van de
monumenten met beschrijving. Daarna gaan we focussen op [Keukenhof](https://cultureelerfgoed.nl/monumenten/511406) de query:

<query data-endpoint="https://linkeddata.cultureelerfgoed.nl/sparql"
       data-output="geo"
       data-query-ref="rce.rq">
</query>

## Minutenplan

Henk/Hans (1 mei) query oud lisse, minutenplannen, eigenaren. (lisse
endpoint) Voor alle…bv. Eigenaren van de 20 monumenten Inzoomen op
keukenhof Hans levert voorlopige query aan Erwin.

<query data-config-ref="https://data.pldn.nl/werkgroep-digitaal-erfgoed/oud-lisse/queries/perceel-achternaam">
</query>

## Rijksmonumenten

Plot rijksmonumenten op een minuutplan. Ellen stuurt WMTS van de
minuutplan aan Hans. Hans kijkt of we dit er even via leaflet en dan
in data story (zonder yasgui) Wouter/Hans hoe resultaat in de data
story te hangen.

## Veldwerken

Rein (15 april) Query veldwerken erbij (pdok labs endpoint) Welke
percelen zijn al die tijd hetzelfde gebleven? Voor keukenhof Wouter
vragen om dit eevn over te nemen.

## Beeldbank

Ellen/Henk/Richard (1 mei) Beeldbanken (rce en lisse/leiden)
[link](https://beeldbank.cultureelerfgoed.nl/alle-afbeeldingen/?q=keukenhof&mode=gallery&view=horizontal), [link](https://beeldbank.cultureelerfgoed.nl/alle-afbeeldingen/?q=511406&mode=gallery&view=horizontal&page=1&reverse=0).  Op een kaart met popups… Of een gallery… (mocht er een audio/video fragment erbij zijn…het kan)
[link](https://beeldbank.cultureelerfgoed.nl/alle-afbeeldingen/?q=keukenhof&mode=gallery&view=horizontal), [link](https://beeldbank.cultureelerfgoed.nl/alle-afbeeldingen/?q=511406&mode=gallery&view=horizontal&page=1&reverse=0).  Lisse/ELO:
[link](http://webservices.picturae.pro/mediabank/media?apiKey=c8bf841e-24cc-11e7-a2f6-4394354bd8f8&fq[]=search_t_collection:%22Vereniging%20Oud%20Lisse%22&q=Keukenhof&CC-O).

Deze urls komen bij in de data van lisse (Hans), en kunnen dan wel
in de visualisatie meegenomen worden. (handwerk; filter de foto’s; een
stuk of 10 uitkiezen en URL opnemen)

## Beroepen

Richard (15 april) Iets met Beroepen. De Beroepen van Lisse op de
kaart.  Beroepen structuur Lisse (organo-gram) (Binnen Lisse kijken
naar de variatie. (alleen de sjieke beroepen?) Wat is de meest
welgestelde straat/wijk van Lisse? Een plaat met kleur
codering. (evt. Een vergelijking met amsterdam)) Richard levert ld
bestandje aan Hans/Henk met query: Dinsdag Hans/Henk: publiceren data:
paar weekjes.

## Historische artikelen

Richard (15 april) kijkt erna…Historische krant artikelen? (is dat
linked data?)
[link](https://www.delpher.nl/nl/platform/results?query=keukenhof&coll=platform),
[link](https://kbresearch.nl/xportal/) Richard kijkt. Deadline: paar
weekjes.

## PDOK

Wouter (1 mei) - Huidige data? (BAG?) (betrouwbaarheid door lisse)
http://nl.dbpedia.org/page/Keukenhof BAG BRT Wikidata (via opnemen van
BAG ids van Lisse in wikidata set) Huidige CBS wijk en buurt gegevens
laten zien… (brouwerij/bier nog even naar kijken; klein duimpje)

<query data-endpoint="https://data.pdok.nl/sparql"
       data-output="geo"
       data-query-ref="brk.rq">
</query>

## Persoon

Henk/Hans (1 mei) (met hulp van Wouter/Richard voor het tweede
deel) Focus op persoon: starten bij een persoon (die meerdere
percelen/buitenhuizen bezit in lisse) (met een mooi fotootje uit de
beeldbank van lisse) Wie zijn de beroemde lissenaren? Hebben die een
portret in musea (collectie in amsterdamse musea; en dan
gestandaardiseerd op personen, zodat je verder kan zoeken in
bv. DBpedia)

## Digitale Collectie Nederland

Digitale Collectie Nederland. Europeana. Bijvoorbeeld:
https://www.europeana.eu/portal/en/record/2021663/memorix_3f05695a_c460_9349_71d3_a5532ff69894.html?q=lisse#dcId=1553596917257&p=1
https://data.collectienederland.nl/search/?q=keukenhof SPARQL endpoint
op: https://data.collectienederland.nl/sparql en grafische schil op
https://data.collectienederland.nl/snorql/ (Richard / Wouter gaan Ivo
Zandhuis nog even navragen)

Richard gaat hier volgende week naar kijken.

## Rijksmuseum

Rijksmuseum data…

## DBpedia

DBpedia query op beroemde personen…

<query data-config-ref="https://triplydb.com/dbpedia/core/queries/lissenaren">
</query>

## NA

Erwin vraagt Ed: welk NA setje mag hier niet ontbreken In de
dataset: gemeentegeschiedenis gebruiken Rein/Erwin/Wouter: maken data
story aan, kopieren tekst.

<query data-config-ref="https://triplydb.com/nationaal-archief/beeldbank/queries/lisse">
</query>

## Tulpen

Erwin-Wouter (15 mei) Iets met namen en bloemennamen….(keukenhof is in de jaren 60 ontstaan) Ludiek ideetje: Voornamen met bloemen (fleur, bloem, madelief, …, misschien via voornamenbank) Tulpen die benoemd zijn naar beroemdheden: is er een beroemde lissenaar met een buitenplaats waarna een tulp is genoemd, en dan doorlinken naar dbpedia europeana, etc…  Serpens (marieke) https://www.clariah.nl/projecten/research-pilots/serpens/serpens#abstract Naturalis (leiden): https://www.nederlandsesoorten.nl/ https://www.wikidata.org/wiki/Property:P3405

<query data-config-ref="https://triplydb.com/dbpedia/core/queries/tulip-hierarchy">
</query>

<query data-config-ref="https://triplydb.com/dbpedia/core/queries/tulip-gallery">
</query>

## Familieboom

<query data-config-ref="https://data.pldn.nl/werkgroep-digitaal-erfgoed/oud-lisse/queries/family-tree">
</query>
