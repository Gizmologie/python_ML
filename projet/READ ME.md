# PROJET : NBA 2021 : Permformance en fonction de l'âge

## Explication du sujet

Les données suivantes ont pour objectifs d'étudier le niveau d'un joueur en fonction de son age, sur la saison NBA 2021.


Le basket est un sport qui se base de plus en plus sur les statistiques. La plus utilisé et la plus révélatrice est le PER qui note l'impact réel d'un joueur sur le terrain. Pour proposer une approche qui n'a pas déjà était faite mainte fois, je n'utiliserai pas cette statistique. 

Pour mettre en valeur les performances des joueurs, je vais m'appuyer sur des informations comme :
- Leur temps de jeu
- le nombre de point marqué(s)
- Les autres grandes lignes statistiques (rebond, passe, interception, contre)
- L'efficacité (les % de shoot réussi)




# Consignes 

### Deadline 

Avant jeudi 19 midi - choisir le dataset et la problématique
A rendre avant vendredi 30 Avril 23h59

## Projet Python data visualisation 

Modalité d’évaluation 
4 compétences évaluées 

Notation sur 20 


Votre analyse sous forme de Jupyter Notebook devra contenir:
Au moins 1 diagramme avec données continues, type nuage de point ou histogramme
Au moins 2 diagramme avec des données discrètes
Au moins 3 graphiques avec des données catégoriques
1 boîte à moustaches avec filtrage des données aberrantes sur le dataset (si il y en a)
1 heat map avec matrice de corrélation (si pertinent)

Des commentaires clairs et pertinents pour chaque graphiques 

dataset : kaggle / paperwithcode / google dataset research


### Compétence évaluée

1) Compréhension du sujet
    - choix de data pertinent + explication du sujet
    - Bien vulgariser le sujet
    - Problématique métier associé
    
2) Structure du Notebook :
    - Comment on répond aux questions données
    - Utilisé des graphiques intéressant au bonne endroit

3) La pertinence du projet :
    - Aspect Graphique (exemple date ilisible = sert à rien => caster des données) 
    - Données lisisble (filtrer données + expliquer comment on a filtré)
    - Pas de warning ou d'erreur ()
    
4) Présentation écrite des résultats
    - Faire des phrases : sujet - verbe - complément
        "Je rappel que ma prob c'était ca, j'avais ce jeu de données la .."
    - Pas juste dire 'je vois un écart type de 2 et une moyenne de 3'
    - Faire des hypothèses

Note :

scatterplot = données discrète (tous les diagramme avec des points)
Nuage de point = rendre toutes les données discrète. Pas toujours pertinent quand on remarque qu'on peut relier les points

Prendre en considération les valeurs qui paraissent abérente si elle représente plus de 5% de l'échantillon

Faire des phrases => je pense que : car : je vois que : on peut penser que 
"c'était dans les contraintes du projet meme si ce n'est pas important pour la suite"
Histogramme de données discrète

lmplot = tendance de données statistiques (graphique de données discrète)


Generate data
durée avec le nombre de point dans un match.