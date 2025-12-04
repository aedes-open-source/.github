# Aedes Open Source

Welkom bij de officiële Aedes Open Source GitHub repository.  

Het doel is om bestaande oplossingen, tools en best practices toegankelijk te maken voor de hele corporatie sector.

> Aedes is niet verantwoordelijk voor de inhoud van deze repositories. Gebruikers zijn zelf verantwoordelijk voor een correcte en rechtmatige toepassing.


## Waarom open source?

Corporaties staan voor flinke maatschappelijke opgaven: Voldoende betaalbare woningen, verduurzaming en leefbare wijken. Veel corporaties werken aan dezelfde vraagstukken en ontwikkelen vergelijkbare (digitale) oplossingen. Door open source principes te hanteren ontstaat een transparant ecosysteem waarin corporaties gezamenlijk werken aan innovatieve oplossingen voor sectorbrede uitdagingen.

* **Gedeelde investering** – niet elke corporatie hoeft afzonderlijk een vergelijkbare oplossing te ontwikkelen.
* **Hogere kwaliteit** – door elkaars expertise en ervaring te benutten, kunnen we sneller verbeteren.
* **Standaardisatie** – gezamenlijke oplossingen zorgen voor meer uniformiteit.
* **Openheid en vertrouwen** – open source maakt zichtbaar hoe we werken en vergroot het onderlinge vertrouwen.


---

## Projecten

### [Woonstad Rotterdam](https://github.com/woonstadrotterdam)

#### 🐍 Python packages

> Zijn te installeren met `pip install <package naam>`

##### 🧮 [woningwaardering](https://github.com/woonstadrotterdam/woningwaardering)

Berekent het aantal woningwaarderingpunten van een woning, op basis van de VERA-standaard.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/woningwaardering)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/woningwaardering)
[![Downloads](https://static.pepy.tech/badge/woningwaardering/month)](https://pepy.tech/project/woningwaardering)
![PyPI - Version](https://img.shields.io/pypi/v/woningwaardering)
![License](https://img.shields.io/github/license/woonstadrotterdam/woningwaardering)

---

##### ⚙️ [pyspark-testframework](https://github.com/woonstadrotterdam/pyspark-testframework)

Bouw gemakkelijk datakwaliteitstests voor PySpark dataframes.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/pyspark-testframework)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/pyspark-testframework)
[![Downloads](https://static.pepy.tech/badge/pyspark-testframework/month)](https://pepy.tech/project/pyspark-testframework)
![PyPI - Version](https://img.shields.io/pypi/v/pyspark-testframework)
![License](https://img.shields.io/github/license/woonstadrotterdam/pyspark-testframework)

---

##### 🧪 [vera-testframework](https://github.com/woonstadrotterdam/vera-testframework)

Test of je data de VERA-standaard volgt m.b.v. PySpark.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/vera-testframework)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/vera-testframework)
[![Downloads](https://static.pepy.tech/badge/vera-testframework/month)](https://pepy.tech/project/vera-testframework)
![PyPI - Version](https://img.shields.io/pypi/v/vera-testframework)
![License](https://img.shields.io/github/license/woonstadrotterdam/vera-testframework)

##### 🏛️ [monumenten](https://github.com/woonstadrotterdam/monumenten)

Bevraag monumentale statussen van het Kadaster en de Rijksdienst voor het Cultureel Erfgoed.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/monumenten)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/monumenten)
[![Downloads](https://static.pepy.tech/badge/monumenten/month)](https://pepy.tech/project/monumenten)
![PyPI - Version](https://img.shields.io/pypi/v/monumenten)
![License](https://img.shields.io/github/license/woonstadrotterdam/monumenten)

---

#### 💬 MCP-servers

> MCP-servers geven extra functionaliteiten aan je AI.

##### 💬📊 [mcp-sqlalchemy](https://github.com/woonstadrotterdam/mcp-sqlalchemy)

MCP-server om SQL-database tools beschikbaar te stellen aan je A.I.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/mcp-sqlalchemy)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/mcp-sqlalchemy)
[![Downloads](https://static.pepy.tech/badge/mcp-sqlalchemy/month)](https://pepy.tech/project/mcp-sqlalchemy)
![PyPI - Version](https://img.shields.io/pypi/v/mcp-sqlalchemy)
![License](https://img.shields.io/github/license/woonstadrotterdam/mcp-sqlalchemy)

---

##### 💬🏛️ [mcp-monumenten](https://github.com/woonstadrotterdam/mcp-monumenten)

MCP-server om monumentale statussen te bevragen met m.b.v. de [monumenten](https://github.com/woonstadrotterdam/monumenten) package.

![Last commit](https://img.shields.io/github/last-commit/woonstadrotterdam/mcp-monumenten)
![GitHub stars](https://img.shields.io/github/stars/woonstadrotterdam/mcp-monumenten)
[![Downloads](https://static.pepy.tech/badge/mcp-monumenten/month)](https://pepy.tech/project/mcp-monumenten)
![PyPI - Version](https://img.shields.io/pypi/v/mcp-monumenten)
![License](https://img.shields.io/github/license/woonstadrotterdam/mcp-monumenten)

---

#### 📊 Datasets

> Kunnen gebruikt worden voor data-analyses en het trainen van AI-modellen.

##### [woningwaarderingen](https://huggingface.co/datasets/woonstadrotterdam/woningwaarderingen)

Dataset met kerneigenschappen van woningen en het aantal woningwaarderingspunten.

##### [monumenten](https://huggingface.co/datasets/woonstadrotterdam/monumenten)

Dataset met alle beschermde stads/dorpsgezichten en Rijks- en gemeentelijke monumenten van Nederland op basis van de Rijksdienst Cultureel Erfgoed en het Kadaster. Wordt paar keer per jaar geüpdatet.

---

#### 🧠 ML/AI modellen

> Voorgetrainde modellen die je kan downloaden en gebruiken.

##### [woningwaardering-ml](https://huggingface.co/woonstadrotterdam/woningwaardering-ml)

Machine-Learning model dat op basis van enkele kerneigenschappen van een woning een schatting kan maken hoeveel woningwaarderingpunten de woning waard is. Is [op deze website](https://huggingface.co/spaces/woonstadrotterdam/woningwaardering-ml-space) interactief uit te proberen!

##### [woningwaardering-llama3-8b-4bit-v1](https://huggingface.co/woonstadrotterdam/woningwaardering-llama3-8b-4bit-v1)

Fine-tuned Llama LLM dat op basis van een fixed-format beschrijving van een woning een schatting kan maken hoeveel woningwaarderingpunten de woning waard is.

---

#####

## Bijdragen

Wil je een open-source project delen via deze Aedes Open Source GitHub? Lees dan de [CONTRIBUTING.md](../CONTRIBUTING.md) voor meer informatie.

---

## Licenties

De licenties zijn op project-niveau gedefinieerd.
