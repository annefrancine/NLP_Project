# NLP_Project

## Préjugés et discrimination : utilisation d’intelligence artificielle pour développer  politiques publiques contre le racisme, la discrimination 
 
### Problématique : 
- Comment aider les chercheurs/ décideurs à identifier et à mettre en œuvre de pratiques factuelles contre la discrimination raciale ? 

### Objectif général : 
- identifier et collecter des rapports de discrimination raciale au Brésil et en France, en plus de proposer et d'évaluer un outil qui aide les chercheurs et les décideurs publics. 

### Objectifs spécifiques : 
- Quels types de discrimination raciale sont fréquemment signalés par les médias et les réseaux sociaux ;
- Comment un outil peut aider les chercheurs et les décideurs en centralisant, classant et quantifiant les signalements de discrimination raciale ? 


## Etapes du projet :  

1) Etat de l’art : Comprendre le racisme en France  
  

2) Web scrapping 

- Identifier les sources d'articles 

- Décider comment utiliser le web scrapping 

- Pour chaque article identifié : extraire tous les articles pour l'évaluation du classificateur, établir un mécanisme d’extraction planifié et stockage des données 

- Classer les articles (sport, monde, quotidien, humour) 

 

3) Stocker les articles dans une base de données non relationnelle  

- Configurer Mongodb 

- Développer une stratégie de stockage et de consultation d'articles 

 

4) Entrainer le modèle NER  

- Développer BERT (Bidirectional Encoder Representations from Transformers) 

- Entrainer NER 

 

5) Entrainer un classificateur des articles  

- Entrainer et tester le classificateur  

 

6) Développer front-end 

7) Développer API 

- Créer les méthodes de l’API 

- Tester l’API 
