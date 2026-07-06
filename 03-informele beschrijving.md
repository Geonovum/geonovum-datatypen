# Informele beschrijving

Informatiemodellen bevatten voor het specificeren van waardetypen van attributen onder andere referenties naar zogenaamde primitieve datatypen. Voorbeelden hiervan zijn: 'CharacterString', 'Integer', 'Date', 'GM_Point', 'Boolean'.

Een primitief datatype wordt primitief genoemd omdat het atomair is dat wil zeggen dat het binnen de context van een informatiemodel niet verder opgesplitst kan worden in kleinere datatypes. Deze primitieve datatypen zijn buiten een informatiemodel gespecificeerd. Meestal in internationale standaarden. Implementaties in een digitale omgeving en implementatie formaten maken dan gebruik van deze internationaal geldende specificaties. ISO/IEC 11404 Information technology - General-Purpose-Datatypes (GPD) beschrijft een primitief datatype als een datatype waarvan de waarderuimte is gespecificeerd door een axioma of door een enumeratie.

Meestal zijn primitieve datatypen enkelvoudig, het kan echter voorkomen dat een primitief datatype een structuur heeft en dus tevens een complex datatype is.

Primitieve datatype worden meestal alleen gebruikt voor het specificeren van waardetypen.

Voor Geonovum willen we afpraken maken over het gebruik van primitieve datatypen, welke het zijn, en wat hun definitie is. We doen dit in de vorm van een handreiking omdat we dit relateren aan internationale standaarden. Deze handreikingen plaatsen die datatypen in de context van de informatiemodellering van Geonovum.

Er wordt een opdeling gemaakt op basis van een aantal onderdelen van het raamwerk van Geostandaarden: de MIM standaard, het ISO 19107 geometrie model en een derde groep 'overig':

> OPMERKING:
> Onderstaande links zijn nu nog naar werkversies
>

- [MIM - Metamodel voor Informatiemodellering](https://geonovum.github.io/mim-datatypen/);

- [Geometrische primitieven conform het geometriemodel van ISO 19107](https://geonovum.github.io/iso-19107-datatypen/);

- Geonovum datatypen. Overige primitieven die niet in bovenstaande groepen vallen. (deze handreiking)

In deze handreikingen worden de primitieve datatypen in een MIM 1.2 \[\[MIM12]] conform conceptueel informatiemodel gespecificeerd. Tevens wordt er een [[NL-SBB-20241010]] conform begrippenmodel gepubliceerd.


## Geonovum datatypen. Overige primitieven die niet in bovenstaande groepen vallen.

Deze derde groep primitieve datatypen is als restgroep gecreëerd om in totaliteit alle primitieve datatypen in de door Geonovum beheerde informatiemodellen in de drie benoemde groepen te omvatten. Een aantal komt uit ISO 19103 maar zit niet in de MIM primitieve datatypen. Dit kan mogelijk aangepast worden. Een aantal zijn ook strikt genomen geen primitieve datatypen en zouden niet voor dat doel gebruikt mogen worden.