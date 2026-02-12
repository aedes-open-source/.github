# Aedes Open Source

Welkom bij de officiële Aedes Open Source GitHub repository.  

Het doel is om bestaande oplossingen, tools en best practices toegankelijk te maken voor de hele corporatie sector.

> [!IMPORTANT]
>  Aedes is niet verantwoordelijk voor de inhoud van deze repositories. Gebruikers zijn zelf verantwoordelijk voor een correcte en rechtmatige toepassing.


## Waarom open source?

Corporaties staan voor flinke maatschappelijke opgaven: Voldoende betaalbare woningen, verduurzaming en leefbare wijken. Veel corporaties werken aan dezelfde vraagstukken en ontwikkelen vergelijkbare (digitale) oplossingen. Door open source principes te hanteren ontstaat een transparant ecosysteem waarin corporaties gezamenlijk werken aan innovatieve oplossingen voor sectorbrede uitdagingen.

* **Gedeelde investering** – niet elke corporatie hoeft afzonderlijk een vergelijkbare oplossing te ontwikkelen.
* **Hogere kwaliteit** – door elkaars expertise en ervaring te benutten, kunnen we sneller verbeteren.
* **Standaardisatie** – gezamenlijke oplossingen zorgen voor meer uniformiteit.
* **Openheid en vertrouwen** – open source maakt zichtbaar hoe we werken en vergroot het onderlinge vertrouwen.

---

## Projecten

### Beveland Wonen - Thuisvester - Woonstad Rotterdam

#### Datasets

#### [woningwaarderingen](https://huggingface.co/datasets/woonstadrotterdam/woningwaarderingen-collab)

Dataset met kerneigenschappen van woningen en het aantal woningwaarderingspunten van de organizaties Beveland Wonen, Thuisvester en Woonstad Rotterdam.

---

### [De Alliantie](https://github.com/de-alliantie)

##### [Ally](https://github.com/de-alliantie/Ally)

Ally is een chatbot voor medewerkers van de klantenservice van de Alliantie. Ally helpt om snel informatie in de kennisbank van de klantenservice met behulp van natuurlijke taal op te zoeken.

##### [Alliantie-AI](https://github.com/de-alliantie/Alliantie-AI)

Alliantie AI is een webapp waarmee medewerkers van de Alliantie op een veilige gebruik kunnen maken van Generative AI toepassingen. Het bestaat uit twee applicaties: Veilig ChatGPT en Notulen Generator.

##### [Verhuiskans](https://github.com/de-alliantie/Verhuiskans)

Verhuiskans is een Machine Learning model die de kans inschat dat een bewoner het huurcontract opzegt. Het model is getrained op historische verhuisdata van de Alliantie.

---

### [Woonstad Rotterdam](https://github.com/woonstadrotterdam)

#### Python packages

> Zijn te installeren met `pip install <package naam>`

##### [woningwaardering](https://github.com/woonstadrotterdam/woningwaardering)

Berekent het aantal woningwaarderingpunten van een woning, op basis van de VERA-standaard.


##### [pyspark-testframework](https://github.com/woonstadrotterdam/pyspark-testframework)

Bouw gemakkelijk datakwaliteitstests voor PySpark dataframes.


##### [vera-testframework](https://github.com/woonstadrotterdam/vera-testframework)

Test of je data de VERA-standaard volgt m.b.v. PySpark.

##### [monumenten](https://github.com/woonstadrotterdam/monumenten)

Bevraag monumentale statussen van het Kadaster en de Rijksdienst voor het Cultureel Erfgoed.

#### MCP-servers

> MCP-servers geven extra functionaliteiten aan je AI.

##### [mcp-sqlalchemy](https://github.com/woonstadrotterdam/mcp-sqlalchemy)

MCP-server om SQL-database tools beschikbaar te stellen aan je A.I.

##### [mcp-monumenten](https://github.com/woonstadrotterdam/mcp-monumenten)

MCP-server om monumentale statussen te bevragen met m.b.v. de [monumenten](https://github.com/woonstadrotterdam/monumenten) package.

#### Datasets

> Kunnen gebruikt worden voor data-analyses en het trainen van AI-modellen.

##### [woningwaarderingen](https://huggingface.co/datasets/woonstadrotterdam/woningwaarderingen)

Dataset met kerneigenschappen van woningen en het aantal woningwaarderingspunten.

##### [monumenten](https://huggingface.co/datasets/woonstadrotterdam/monumenten)

Dataset met alle beschermde stads/dorpsgezichten en Rijks- en gemeentelijke monumenten van Nederland op basis van de Rijksdienst Cultureel Erfgoed en het Kadaster. Wordt paar keer per jaar geüpdatet.

#### ML/AI modellen

> Voorgetrainde modellen die je kan downloaden en gebruiken.

##### [woningwaardering-ml](https://huggingface.co/woonstadrotterdam/woningwaardering-ml)

Machine-Learning model dat op basis van enkele kerneigenschappen van een woning een schatting kan maken hoeveel woningwaarderingpunten de woning waard is. Is [op deze website](https://huggingface.co/spaces/woonstadrotterdam/woningwaardering-ml-space) interactief uit te proberen!

##### [woningwaardering-llama3-8b-4bit-v1](https://huggingface.co/woonstadrotterdam/woningwaardering-llama3-8b-4bit-v1)

Fine-tuned Llama LLM dat op basis van een fixed-format beschrijving van een woning een schatting kan maken hoeveel woningwaarderingpunten de woning waard is.

---

### [Thuisvester](https://www.thuisvester.nl/)

##### [woningwaarderingen](https://huggingface.co/datasets/Thuisvester/woningwaardering)

Dataset met kerneigenschappen van woningen en het aantal woningwaarderingspunten.

---

### [Beveland Wonen](https://bevelandwonen.nl/)

##### [woningwaarderingen](https://huggingface.co/datasets/BevelandW/wws)

Dataset met kerneigenschappen van woningen en het aantal woningwaarderingspunten.

---

## Bijdragen

Wil je een open-source project delen via deze Aedes Open Source GitHub? Lees dan de [CONTRIBUTING.md](../CONTRIBUTING.md) voor meer informatie.

---

## Licenties

De licenties zijn op project-niveau gedefinieerd.
