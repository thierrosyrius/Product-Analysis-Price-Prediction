Analyse des produits IKEA et précision des prix à l’aide de la régression linéaire
IKEA est une entreprise de conception de meubles spécialisés dans la vente de meubles emballé à plat, d’appareils de cuisine et d’autres accessoires pour la maison. 
IKEA a pour vision de créer une vie quotidienne meilleure pour le plus grand nombre grâce à ses produits. Cette vision va au-delà de l’ameublement de la maison et va un impact positif sur le monde des communautés pour aider nos clients à vivre une vie plus durable a la maison
IKEA se met constamment au défi met les autres au défi de faire plus avec moins sans faire de compromis sur la qualité. Chaque jour, partout, IKEA fait de son mieux pour découvrir et éliminer les couts inutiles, car les bas prix sont impossibles sans les bas couts
1.	Régression linéaire
La régression linéaire d’apprentissage automatique supervise qui tente de modéliser une relation automatique entre les variables dépendantes (Y) et les variables indépendantes(x). Pour chaque observation évaluée avec un modèle, la valeur réel cible (Y) est comparée à la valeur prédite de la cible(y), et les principales différentes entre ces valeurs sont appelées résidus. Le modèle de régression linéaire vise à minimiser la somme de tous les carrés des résidus.
2.	Evaluation du modèle :
•	Mean Absolute Error (MAE) : Moyenne des valeurs absolues des erreurs de prédiction individuelles sur toutes les instances de l’ensemble de test.
•	Root Mean Square Error (RMSE) : l’écart type des résidus (erreurs de prédiction)
•	Mean Absolute Percentage Error (MAPE) : est une mesure de précision de prédiction d’une méthode de prévision en statistique.
•	Facteur d’inflation de la variance (VIF) : est un outil permettant d’identifier le degré de multi colinéarité.
3.	Régression de RIDGE
Nous devons savoir quelle est la meilleure valeur lambda pour notre modèle de régression linaire [0.01,0.1, 1,10]. Lambda est un paramètre utilise pour la régularisation. Il est utilisé pour éviter le surajustement.
4.	Régression LASSO
Comme régression ridge, nous devons savoir quelle est la meilleure valeur lambda pour notre modèle de régression linéaire [0.01,0.1,1,10], pour éviter le surajustement
5.	Conclusion
Sur la base de notre produit de modélisation de prévision des prix, RIDGE et LASSO concluent aux mêmes résultats. Les fonctionnalités qui ont eu un impact positif sur le prix du produit sont sellable_online (disponibilité du produit en ligne) et category (categorie de produit). Tandis que other_colors et price_diff (prix diffèrent entre le prix actuel et l’ancien) ont eu une incidence négative sur le prix du produit.
Les produits disponibles en ligne ont une probabilité de prix élevée que les produits qui ne vendent que hors ligne, cela signifie qu’IKEA doit augmenter ses ventes en ligne. Cela aidera également à augmenter les ventes de marchandises avec un cout opérationnel minimum.
IKEA doit créer un produit exclusivement disponible en ligne, mais avec un affichage de produit hors ligne, afin d’attirer les clients lorsqu’ils viennent dans un magasin hors ligne et de visiter le site web pour un achat en ligne.
IKEA doit se concentrer sur la création de produits avec une option de couleur minimisée, pour aider à réduire les couts de production et optimiser les variétés de produit en fonction des besoins des clients.

