# LudiStore — fidélité et saisonnalité

Séparer croissance, saisonnalité et fidélité ; tester une prévision hors période.

## Résultats
- 179,930 lignes rapprochées ; statistiques clients calculées au grain client.
- Spearman âge/dépense : 0.006 ; taille d’effet Kruskal : 0.0004.
- MAE ETS six mois : 5,584 EUR ; baseline : 24,545 EUR.

## Actions
- Retenir une prévision seulement si elle améliore la référence saisonnière.
- Comparer les cohortes à ancienneté égale.

## Limites
- Tests descriptifs sur simulation, aucune causalité réelle.
- Bootstrap des résidus indicatif, sans garantie de couverture avec autocorrélation.
- Cellules des cohortes non observées vides ; elles ne valent pas zéro.
