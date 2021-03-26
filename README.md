# <font color="purple">Data-Analyst | Projet 9 | Prédire la demande en électricité</font>

## <font color="orange">Compétences évaluées :</font>
- Maitriser les méthodes de lissage et la méthode de Holt-Winters
- Maitriser les notions de composantes et de modèles de décomposition
- Maitriser la méthode ARMA
- Représenter graphiquement une série temporelle

## <font color="purple">Mise en situation :</font>
Data Analyst employé d'une société coopérative qui s'est développée grâce à la libéralisation du marché de l’électricité en France. Elle est spécialisée dans les énergies renouvelables.

La plupart de ces énergies renouvelables est cependant intermittente, il est donc difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

Les tâches à effectuer :
- Corriger les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
- Effectuer une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles.
- Effectuer une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle. 

## <font color="purple">Données initiales :</font>
Un jeu de données initial contient :

- Données mensuelles de consommation totale en énergie,
- Données météo.
