# Iteratie rapport 5

Hieronder een overzicht van mijn voortgang in de vijfde iteratie.\
De `-` in tabel geeft het niveau in de vorige iteratie aan, een maakt daarmee de groei zichtbaar.

|                    | Advanced | Proficient | Beginning | Orienting | Undefined |
|--------------------|:--------:|:----------:|:---------:|:---------:|:---------:|
| 1 Analysis         |          |     x      |           |           |           |
| 2 Advice           |          |     x      |           |           |           |
| 3 Design           |          |     x      |     -     |           |           |
| 4 Implementation   |          |     x      |     -     |           |           |
| 5 Management       |          |     x      |           |           |           |
| 6 Judgement        |          |     x      |           |           |           |
| 7 Communication    |          |     x      |           |           |           |
| 8 Learning ability |          |     x      |           |           |           |

---
# Verklaring

## 1. Analysis
Deze iteratie heb ik de feedback van de vorige iteratie over de acceptatie testen verwerkt.\
Hierbij heb ik de stappen duidelijker gemaakt, wat de actor moet doen, wat het systeem laat zien of doet.\
En ik heb waar mogelijk alternatieve flows toegevoegd.
De Acceptatie testen zijn [hier](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Documenten/1.%20Acceptatie%20tests.md) te vinden,

## 2. Advice
Niet aangeraakt deze iteratie.

## 3. Design
Deze iteratie heb ik voor design mij bezig gehouden met het ontwerpen van de API.\
Hierbij heb ik een OpenAPI document opgesteld dat de API beschrijft.\
Deze is [hier](https://github.com/S7HaMachineLearning/documentation/blob/main/S7HaMachineLearning/Onderzoeken/Bram/7.%20API%20doc.yaml) te vinden.

Deze is in te laden in [Swagger](https://editor.swagger.io/) om een visuele representatie te krijgen van de API.


## 4. Implementation

Voor het AA Backen project heb ik een extra pipeline toegevoegd die de gebruikte dependencies controleert op kwetsbaarheid en deze rapporteert.\
De pipeline (Github action) is [hier](https://github.com/S7HaMachineLearning/AA_backend/blob/main/.github/workflows/lint_test.yml) te vinden, en een van de geslaagde runs is [hier](https://github.com/S7HaMachineLearning/AA_backend/actions/runs/5014355533) te vinden.

En ook heb ik een start gemaakt met het front-end project dat gebruikt maakt van de API.\
Het project is gebaseerd op de POC die ik eerder gemaakt heb.\
Op dit moment is alleen de eerste use-case geïmplementeerd, toevoegen van een HA sensor aan de applicatie.\
Deze is [hier (AA_frontend)](https://github.com/S7HaMachineLearning/AA_frontend) te vinden.
In het project heb ik ook een pipeline toegevoegd die de code build, lint en dependencies controleert op kwetsbaarheid.\ 


## 5. Management
Niet aangeraakt deze iteratie.

## 6. Judgement
Niet aangeraakt deze iteratie.

## 7. Communication
Niet aangeraakt deze iteratie.

## 8. Learning ability
Niet aangeraakt deze iteratie.
