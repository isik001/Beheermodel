# Inleiding

## Leeswijzer


Dit document beschrijft hoe Logius, afdeling Stelselregie de Peppol standaard beheert en hoe de bijbehorende governance is ingericht.

## _Vul naam van de standaard hier in_

Beschrijf hier de standaard

<aside class="example">
De Peppol-standaard is een internationale set van afspraken en technische specificaties waarmee organisaties elektronisch documenten kunnen uitwisselen, zoals facturen, orders,time-cards en ordersbevestigingen.
In de kern zorgt Peppol ervoor dat verschillende systemen wereldwijd met elkaar kunnen communiceren via één gestandaardiseerd netwerk. 

De standaard bestaat uit drie belangrijke onderdelen:
Technische specificaties (zoals UBL/XML): hierin staat hoe documenten worden opgebouwd, zodat systemen ze kunnen lezen en verwerken.
Transportinfrastructuur (het Peppol-netwerk): een veilig netwerk dat zorgt voor de verzending van berichten tussen partijen via Access Points.
Afspraken en governance (OpenPeppol): regels en standaarden die ervoor zorgen dat alle deelnemers op dezelfde manier werken en interoperabel blijven.

Het gebruik van Peppol zorgt voor:
één aansluiting met wereldwijde bereikbaarheid (Connect Once, Reach All)
veilige en betrouwbare uitwisseling van documenten, minder handmatige verwerking, snellere en foutloze administratieve processen, internationale interoperabiliteit
Kort gezegd: Peppol is een gestandaardiseerd digitaal “afsprakenstelsel” dat het mogelijk maakt om wereldwijd op dezelfde manier elektronische zakelijke documenten uit te wisselen. 

VOORBEELD 1
Stel, een IT-leverancier levert diensten aan zowel een gemeente als een ziekenhuis in Nederland. Zonder Peppol zou de leverancier vaak per organisatie andere manieren moeten gebruiken om facturen aan te leveren (e-mail, portalen, pdf’s of verschillende e-factuurkoppelingen).

Met Peppol werkt het zo:
De leverancier sluit één keer aan op het Peppol-netwerk via een Access Point. Vanuit het eigen boekhoudsysteem wordt een standaard Peppol-factuur verstuurd. De factuur gaat via het Peppol-netwerk naar de juiste overheidsorganisatie of zorginstelling.
De gemeente en het ziekenhuis ontvangen de factuur automatisch in hun eigen financiële systeem, volledig verwerkt volgens dezelfde standaard. 

Resultaat: één aansluiting waarmee je alle aangesloten Nederlandse overheidsorganisaties en steeds meer zorginstellingen kunt bereiken  dat is Connect Once, Reach All in de Nederlandse praktijk.

### Nut

Beschrijf hier de nut van de standaard

<aside class="example">
De Peppol-standaard is nuttig omdat het zorgt voor één uniforme manier om elektronische documenten, zoals facturen en orders, uit te wisselen tussen organisaties.

De belangrijkste waarde zit in:

Interoperabiliteit: systemen kunnen direct met elkaar communiceren, ongeacht software of land.
Eén standaard in plaats van maatwerk: organisaties hoeven niet voor elke klant of leverancier aparte koppelingen te bouwen.
Efficiëntie: minder handmatige handelingen, snellere verwerking van documenten en minder fouten.
Kostenbesparing: minder beheer en onderhoud van allerlei verschillende integraties.
Betrouwbaarheid en veiligheid: uitwisseling verloopt via een gecontroleerd netwerk met duidelijke afspraken en standaarden.
Schaalbaarheid: met één aansluiting kun je een groot internationaal netwerk bereiken (Connect Once, Reach All).
Digitalisering van ketens: versnelt de overgang naar volledig digitale en geautomatiseerde administratieve processen.
</aside>

### Werking

Beschrijf hier de werking van de standaard

<aside class="example">
Een application programming interface (API) is een gestructureerd en
gedocumenteerd koppelvlak voor communicatie tussen applicaties. Zo
lang er computers zijn, bestaan er API's en worden er verschillende
API technologieën gebruikt. In de laatste 10 jaar heeft
Representational state transfer (REST) zich ontwikkeld tot een
bepalend principe voor het realiseren van API's. Zogenaamde
‘REST-API's’ doen voor applicaties wat websites voor mensen doen.
Websites presenteren informatie aan mensen, REST-API's maken
applicaties en gegevens over het Internet beschikbaar voor andere
applicaties. De technologie achter websites en REST-API's heeft daarom
veel gemeen.

De overheid gebruikt REST-API's voor koppelingen met andere overheden,
bedrijven en indirect ook met burgers, bijvoorbeeld via mobiele apps
en webapps die aangeboden worden door bedrijven of overheden zelf.
Ontwikkelaars kunnen deze REST-API's bevragen vanuit de gangbare
programmeertalen en frameworks zoals Python, Java, Microsoft C\#, PHP.
</aside>

### Status

Beschrijf hier de status van de standaard

<aside class="example">
De actuele versie van de ADR-standaard is 1.0. Deze versie is op
09-07-2020 door het OBDO vastgesteld op advies van het Forum
Standaardisatie.
</aside>

## BOMOS

> ![](./media/image3.png)Logius richt de beheerorganisatie in conform
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
