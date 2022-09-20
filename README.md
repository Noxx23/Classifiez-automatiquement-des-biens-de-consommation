# Classifiez-automatiquement-des-biens-de-consommation
Réaliser une première étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article.

Utiliser :
   - deux approches de type `bag-of-words`, comptage simple de mots et Tf-idf ;
   - une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
   - une approche de type word/sentence embedding avec BERT ;
   - une approche de type word/sentence embedding avec USE (Universal Sentence Encoder). 

Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :

   - un algorithme de type SIFT / ORB / SURF ;
   - un algorithme de type CNN Transfer Learning.
   
## Compétences évaluées

- [ ] Prétraiter des données texte pour obtenir un jeu de données exploitable
- [ ] Représenter graphiquement des données à grandes dimensions
- [ ] Prétraiter des données image pour obtenir un jeu de données exploitable
- [ ] Mettre en œuvre des techniques de réduction de dimension
