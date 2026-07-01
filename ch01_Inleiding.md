# Inleiding

## Leeswijzer

>Dit document beschrijft hoe Logius, afdeling Stelselregie de Peppol standaard beheert en hoe de bijbehorende governance is ingericht.

## _Peppol_

Beschrijf hier de standaard
<aside class="example">

</aside>

### Nut
De Peppol-standaard is een internationale set van afspraken en technische specificaties waarmee organisaties elektronisch documenten kunnen uitwisselen, zoals facturen, orders,time-cards en ordersbevestigingen. 
In de kern zorgt Peppol ervoor dat verschillende systemen wereldwijd met elkaar kunnen communiceren via één gestandaardiseerd netwerk. 

De standaard bestaat uit drie belangrijke onderdelen:
Technische specificaties (zoals UBL/XML): hierin staat hoe documenten worden opgebouwd, zodat systemen ze kunnen lezen en verwerken.
Transportinfrastructuur (het Peppol-netwerk): een veilig netwerk dat zorgt voor de verzending van berichten tussen partijen via Access Points.
Afspraken en governance (OpenPeppol): regels en standaarden die ervoor zorgen dat alle deelnemers op dezelfde manier werken en interoperabel blijven.

Het gebruik van Peppol zorgt voor:
één aansluiting met wereldwijde bereikbaarheid (Connect Once, Reach All)
veilige en betrouwbare uitwisseling van documenten
minder handmatige verwerking
snellere en foutloze administratieve processen
internationale interoperabiliteit
Kort gezegd: Peppol is een gestandaardiseerd digitaal “afsprakenstelsel” dat het mogelijk maakt om wereldwijd op dezelfde manier elektronische zakelijke documenten uit te wisselen. 

VOORBEELD 1
Stel, een IT-leverancier levert diensten aan zowel een gemeente als een ziekenhuis in Nederland.

Zonder Peppol zou de leverancier vaak per organisatie andere manieren moeten gebruiken om facturen aan te leveren (e-mail, portalen, pdf’s of verschillende e-factuurkoppelingen).

Met Peppol werkt het zo:

De leverancier sluit één keer aan op het Peppol-netwerk via een Access Point.
Vanuit het eigen boekhoudsysteem wordt een standaard Peppol-factuur verstuurd.
De factuur gaat via het Peppol-netwerk naar de juiste overheidsorganisatie of zorginstelling.
De gemeente en het ziekenhuis ontvangen de factuur automatisch in hun eigen financiële systeem, volledig verwerkt volgens dezelfde standaard.
Resultaat: één aansluiting waarmee je alle aangesloten Nederlandse overheidsorganisaties en steeds meer zorginstellingen kunt bereiken  dat is Connect Once, Reach All in de Nederlandse prak


### Werking
De werking van de Peppol-standaard draait om een combinatie van afspraken, formaten en een beveiligd netwerk waarmee organisaties elektronische documenten met elkaar kunnen uitwisselen.

In de praktijk werkt het zo:
Documentopmaak (standaard formaat)
Een organisatie maakt een document aan, zoals een factuur, in een gestandaardiseerd formaat (bijvoorbeeld UBL/XML). Dit zorgt ervoor dat alle systemen dezelfde “taal” spreken.
Verzenden via Peppol Access Point
Het document wordt vanuit het eigen systeem verstuurd naar een Peppol Access Point. Dit is een soort beveiligde gateway naar het Peppol-netwerk.
Routing via het Peppol-netwerk
Het netwerk zorgt ervoor dat het bericht op basis van adressering (Peppol ID) bij de juiste ontvanger terechtkomt. Dit gebeurt veilig en gecontroleerd, zonder dat partijen direct met elkaar hoeven te koppelen.
Ontvangst via Access Point van de ontvanger
Het Access Point van de ontvangende organisatie haalt het bericht op uit het netwerk en levert het af in hun eigen systeem.
Verwerking in het systeem
De ontvanger kan het document automatisch verwerken in zijn financiële of administratieve systeem, zonder handmatige invoer.


### Status
De status van de Peppol-standaard is op dit moment die van een breed geadopteerde, volwassen internationale e-procurement- en e-invoicing standaard die actief in gebruik én in doorontwikkeling is.

Kernpunten van de status:
Internationaal breed geaccepteerd: Peppol wordt gebruikt in steeds meer landen binnen Europa en daarbuiten, zowel door overheden als steeds meer private partijen.
Sterk verankerd in publieke sector: in veel landen is Peppol (of Peppol-gebaseerde e-facturatie) de standaard voor communicatie met overheden.
Groeiende adoptie in zorg en private sector: naast overheid wordt de standaard steeds vaker gebruikt in sectoren zoals zorg, logistiek en grote supply chains.
Beheerd door OpenPeppol: de standaard wordt continu doorontwikkeld door de internationale community 
Actieve evolutie: de standaard is niet “af”, maar groeit mee met nieuwe Europese regelgeving (zoals e-invoicing en ViDA) en nieuwe use cases.
De facto interoperabiliteitsstandaard: in veel domeinen is Peppol inmiddels de praktische standaard geworden voor grensoverschrijdende digitale documentuitwisseling.

./media/image3.png)Logius richt de beheerorganisatie in conform
> het Beheer en Ontwikkel Model voor Open Standaarden (BOMOS). Ook het
> beheer van de xxxxx is op basis van BOMOS ingericht. Voor de
> beheerorganisatie heeft Logius een generiek beheermodel opgezet, waar
> het beheerplan van xxx is afgeleid.

![](./media/image1.png)

*Figuur 1 Bomos model*

![](./media/image5.png)Voor meer informatie over BOMOS zie ook:

[<span class="underline">BOMOS, het
fundament</span>](https://gitdocumentatie.logius.nl/publicatie/bomos/fundament/)

[<span class="underline">BOMOS, de
verdieping</span>](https://gitdocumentatie.logius.nl/publicatie/bomos/verdieping/)

[<span class="underline">'Publicatie-BOMOS-2i.pdf'</span>](https://www.forumstandaardisatie.nl/sites/default/files/BFS/4-basisinformatie/publicaties/Publicatie-BOMOS-2i.pdf)

BOMOS onderscheidt verschillende levenscyclusfases waarin een
standaard zich kan bevinden. Deze fase bepaalt mede op welke
beheeronderdelen meer of minder wordt ingezet. De verschillende fases
zijn:

1.  Creatie/ontwikkeling
2.  Introductie
3.  Implementatie/groei
4.  Volwaardige toepassing
5.  Uitfaseren

![](./media/image7.png)![](./media/image8.png)Adoptie

![](./media/image10.png)

Tijd

*Figuur 2 Bomos levenscyclus*

De xxx bevindt zich in de xxx fase. De eerste versie van de standaard
is xxx aangemeld bij het Forum Standaardisatie en op xxx op de lijst
van verplichte standaarden opgenomen. Vanuit het xxx en Logius
afdeling Standaarden wordt momenteel nog volop aan de xxx gewerkt en
de verwachting is dat de standaard nog de nodige ontwikkelingen door
gaat maken.

Daarom is er komende tijd vooral aandacht voor:

Het in de praktijk bestendigen van het beheer van de standaard;
Gestaag doorontwikkeling van de specificaties zelf;

Bouwen en aanbieden ondersteunende tooling; Groei in het aantal
toepassingen van de standaard; Monitoring van het gebruik van de
standaard; Groei van de community rond de standaard.
