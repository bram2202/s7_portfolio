# Iteratie rapport 4

Hieronder een overzicht van mijn voortgang in de vierde iteratie.\
De `-` in tabel geeft het niveau in de vorige iteratie aan, een maakt daarmee de groei zichtbaar.

|                    | Advanced | Proficient | Beginning | Orienting | Undefined |
|--------------------|:--------:|:----------:|:---------:|:---------:|:---------:|
| 1 Analysis         |          |     x      |     -     |           |           |
| 2 Advice           |          |     x      |     -     |           |           |
| 3 Design           |          |            |     x     |     -     |           |
| 4 Implementation   |          |            |     x     |     -     |           |
| 5 Management       |          |     x      |     -     |           |           |
| 6 Judgement        |          |     x      |     -     |           |           |
| 7 Communication    |          |     x      |           |           |           |
| 8 Learning ability |          |     x      |           |           |           |

---
# Verklaring

## 1. Analysis
Voor het testen van de web applicatie heb ik acceptatie tests gemaakt die verschillende functies van de applicatie testen.\
Deze zijn opgesteld aan de hand van het requirements document. zie [Acceptatie test - User interface](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Documenten/1.%20Acceptatie%20tests.md#user-interface).

### Volgende stap
?

## 2. Advice
Deze iteratie ben ik begonnen met het nadenken over de database,\
Het eerste wat ik gedaan heb is een klein onderzoek naar welke type database het best aansluit bij de applicatie.\
Zie [Database voor gebruik in Python Backend](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Onderzoeken/Bram/6.%20Onderzoek%20-%20Python%20database.md#database-voor-gebruik-in-python-backend).\
Met de uitkomst hiervan ben ik door gegaan met het ontwerpen van een database schema.

Tevens heb ik bij de modellen uit de vorige iteratie text toegevoegd om zo verkeerde interpretatie van de lezer weg te nemen.

### Volgende stap
?

## 3. Design
Na de keuzen voor een relationele database heb ik een entity relationship diagram gemaakt.\
Zie [Database schema](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Onderzoeken/Bram/Design/entity%20diagram.png)

Ook ben ik bezig geweest met een [Flow diagram](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Onderzoeken/Bram/Design/flow_sensors.png) voor de sensor label flow,\
en een simple [sequence diagram](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Onderzoeken/Bram/Design/seq_diagram.png) om de afhankelijkheid met Home Assistant aan te tonen.

### Volgende stap
?

## 4. Implementation
Deze iteratie ben ik gestart met het maken van het python backend voor de applicatie.\
Deze is te vinden op [Github](https://github.com/S7HaMachineLearning/AA_backend).\
Hij is gebaseerd op de POC die ik eerder gemaakt heb.

### Volgende stap
?

## 5. Management
Voor het backend project zijn er twee Github actions (pipelines) toegevoegd.\
Een voor het uitvoeren van unit testen van de applicatie.
En een voor het Linten van de code, zodat deze aan de standaard voldoet om zo fouten te voorkomen en de kwaliteit en leesbaarheid te waarborgen.
De actions zijn [hier](https://github.com/S7HaMachineLearning/AA_backend/actions) te vinden.

### Volgende stap
Voor de stap naar Advanced moet er een pipeline komen die de applicatie kan kan builden in een docker image en deze kan uploaden naar een container registry.

## 6. Judgement
"Met het beantwoorden en beredeneren van de hoofdvraag kom je op Proficient."

***De hoofdvraag:***
```
Ontwikkel een full stack component waarmee de home assistant gebruiker feedback kan geven op de voorspellingen zodat de sensoren gelabeld kunnen worden en dat er feedback gegeven kan worden op de gegenereerde automations.
```

Door verschillende onderzoeken uit te voeren en proof-of-concepts te maken blijkt dit mogelijk te zijn:
- Python back-end die een API host en een machine learning model kan aanroepen.
- Angular met het ionic framework als front-end voor de user interface die praat met het Python back-end.
- SQLite als database voor het opslaan van de data.
- Een docker image waarin de front-end en back-end en database samen komen om gebruikt te worden in Home Assistant als een Add-on.

### Volgende stap
?

## 7. Communication
Niet aangeraakt deze iteratie.
### Volgende stap
?

## 8. Learning ability
Niet aangeraakt deze iteratie.
### Volgende stap
?