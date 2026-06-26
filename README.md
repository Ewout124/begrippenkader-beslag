# Begrippenkader Strafvorderlijk Beslag

## Inleiding

Deze repository bevat het begrippenkader voor het domein **Strafvorderlijk Beslag**.

Het begrippenkader beschrijft de betekenis van de begrippen die binnen het domein worden gebruikt en vormt daarmee de semantische basis voor informatiemodellering, gegevensuitwisseling en interoperabiliteit.

Hoewel het begrippenkader is opgesteld voor het domein Strafvorderlijk Beslag, is de gehanteerde werkwijze in beginsel toepasbaar op andere domeinen binnen de strafrechtketen.

---

# Doelstellingen

Met dit project worden de volgende doelstellingen nagestreefd:

* het vastleggen van eenduidige en consistente definities van begrippen;
* het bevorderen van een gemeenschappelijk begrippenkader voor alle betrokken organisaties;
* het ondersteunen van informatiemodellen;
* het ondersteunen van gegevensuitwisseling;
* het bieden van een semantische basis voor API-specificaties;
* het vergroten van de interoperabiliteit tussen organisaties en systemen.

---

# Scope

Deze repository richt zich uitsluitend op de semantische beschrijving van begrippen.

Procesbeschrijvingen, gegevensmodellen en technische implementaties vallen buiten de scope van dit project, maar kunnen in de toekomst op het begrippenkader worden gebaseerd.

---

# Uitgangspunten

Het begrippenkader wordt ontwikkeld volgens een aantal vaste uitgangspunten.

* Begrippen beschrijven de betekenis van concepten.
* Definities zijn eenduidig en niet-circulair.
* Definities beschrijven niet de inrichting van processen of systemen.
* Juridische begrippen worden onderscheiden van informatiekundige begrippen.
* Consistentie heeft voorrang boven volledigheid.
* Nieuwe begrippen worden alleen toegevoegd wanneer zij aantoonbare semantische meerwaarde hebben.

---

# Relatie met standaarden

Het begrippenkader sluit waar mogelijk aan bij bestaande standaarden en methodieken, waaronder:

* Nederlandse standaard voor het beschrijven van begrippen (NL-SBB);
* Metamodel Informatiemodellering (MIM);
* W3C PROV;
* SKOS;
* CCTS.

Deze standaarden worden niet als doel op zichzelf beschouwd, maar als hulpmiddelen om de kwaliteit en herbruikbaarheid van het begrippenkader te vergroten.

---

# Repository-structuur

```text
excel/
    Bronbestand van het begrippenkader

docs/
    Ontwerpdocumentatie
    Begripstypering
    Redactieproces

notes/
    Werknotities
```

---

# Documentatie

De belangrijkste ontwerpkeuzes zijn vastgelegd in de volgende documenten.

* [Ontwerpprincipes](docs/Ontwerpprincipes.md)
* [Begripstypering](docs/Begripstypering.md)
* [Redactieproces](docs/Redactieproces.md)

Deze documenten vormen samen de methodische basis voor de verdere ontwikkeling van het begrippenkader.

---

# Ontwikkelwijze

Het begrippenkader wordt iteratief ontwikkeld.

Bij iedere wijziging wordt aandacht besteed aan:

* juridische juistheid;
* semantische juistheid;
* onderlinge consistentie;
* modelleerbaarheid;
* herbruikbaarheid.

Waar nodig worden definities aangescherpt, begrippen herzien of nieuwe begrippen voorgesteld. Alle inhoudelijke wijzigingen worden gemotiveerd.

---

# Toekomstige uitbreidingen

De ambitie is dat het begrippenkader op termijn als semantische referentie kan dienen voor onder meer:

* informatiemodellen;
* API-specificaties;
* W3C PROV-modellen;
* SKOS-vocabulaires;
* RDF-ontologieën;
* JSON-LD-contexten.

Deze representaties maken geen onderdeel uit van de huidige repository, maar kunnen in een later stadium uit het begrippenkader worden afgeleid.

---

# Status

Het project bevindt zich in ontwikkeling.

Het begrippenkader wordt stapsgewijs inhoudelijk geredigeerd en semantisch aangescherpt. De documentatie groeit mee met de inzichten die tijdens dit proces worden opgedaan.
