**Team 3 - Fleming**

Prédiction de la mortalité de manière dynamique pour un patient à un horizon de qq jours

**04/04/2018**
- exploration des données, 
- discussions sur la manière de constituer les cohorts (âge, sexe, cholestérol moyen, fréquence cardiaque moyenne, pression artérielle moyenne, taille, poids, nb d'allergies, etc.), 
- stats importantes à obtenir: durée de séjours par unité (influence sur le nb d'observations), taux de mortalité et fréquence par diagnostics et par année, idem par unité, stats sur les indicateurs classiques par cohort.


TODO :
- [ ] Accès à MIMIC PostGreS en python directement
- [ ] Benchmarker tous les indicateurs principaux (SOFA, IGS-II) et écrire des scripts pour les calculer.
- [ ] Réaliser un EDA complet (jupyter notebook) pour se faire une idée des biais existants (cf. idée de stats du 04/04)
- [ ] Avec ces résultats, créer nos propres indicateurs et en discuter avec le médecin référent (éventuellement les calculer sur des données d'hopitaux parisiens)
- [ ] Définir la mesure précise qu'on souhaite prédire (par itération sur la période temporelle entre autres)
- [ ] Benchmark des différents modèles suivant qq métriques dont: précision, nombre de variables explicatives, complexité d'entraînement du modèle (souci de reproductibilité).

