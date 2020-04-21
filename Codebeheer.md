# CONCEPT VERSIE : Codebeheer Open Webconcept
Tenbehoeve van het beheer van de code is het noodzakelijk om afspraken te maken, zodat iedereen weet waar men aan toe is.

## Gedachte Open Webconcept
Binnen het Open Webconcept hanteren we de volgende uitgangspunten:
* WordPress
* Open architectuur:
* Vrije marktwerking
* Open samenwerking
* Pragmatisch
Intentieverklaring op: https://OpenWebconcept.nl/intentieverklaring/

## Open Webconcept Bouwblokken
Binnen het Open Webconcept delen we functionaliteiten door middel van bouwblokken, hiervoor gelden de volgende uitgangspunten:
* Te gebruiken in WordPress 
* Commonground gedachte
* Delen met anderen 
* Helpen met fouten
* Het is een Datadienst of een Toepassing

## Behoefte Bouwblokken
Voor deze bouwblokkken kunnen we dan ook bepaalde eisen ophalen:
* Wordpress: opensource
* Toegankelijk voor nieuwe nieuwe partijen  die willen participeren
* Pragmatische insteek, alleen formeel wanneer het nodig is
* Ook een reeële manier om weer te verlaten
* Garanties ten opzichte van elkaar
* WordPress installer : https://github.com/VNG-Realisatie/Open Webconcept (moet https://github.com/Open Webconcept/  worden)
* Losse componenent:
	* Code deelbaar
	* Zelfde licentie
	* 2e lijns support op de code (bugs/changes)
	* Eén jaar aangeven dat support vervalt
	* Eén plek waar alle bouwblokken te vinden zijn 
	* Signaal wanneer er een nieuwe versie is

## Invulling Bouwblokken
Per bouwblok:
* Te vinden op https://github.com/organizations/Open Webconcept/
* Licentie is EUPL
* Eén repository met die bloknaam
* Wordpress notificatie wanneer er een update is
* Gemeente is beheerder bouwblok
* Leverancier plaats de code en maakt doet de aanpassingen (kan natuurlijk een gemeente zijn)
* Dat de issues/changes worden opgepakt
* Installeerbaar via de  Open Webconcept plugin structuur
* De blokken kunnen met elkaar draaien op dezelfde server maar mogen ook los geinstalleerd worden

## Beheer organisatie
Open Webconcept Foundation : 
* Beheert https://github.com/OpenWebconcept
* Beheert afspraken (https://github.com/OpenWebconcept/Afspraken/)
* Bijhouden wordpress plugin lijst (json)
* Aanmaken repositories
* Rechten  aan gemeenten geven op repository
Gemeente:
* Rechten aan leverancier geven op repository
* Garant staan voor de repository
Leverancier
* Plaatst de code in de betreffende  repository
* Zorgt dat de bugs worden opgelost
* Handelt de issues / changes af
