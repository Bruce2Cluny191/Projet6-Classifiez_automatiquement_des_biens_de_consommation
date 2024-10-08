# Classification Automatique des Biens de Consommation

## Contexte

Dans le cadre du développement d'une marketplace e-commerce, l'entreprise "Place de marché” souhaite automatiser la classification des articles pour améliorer la fiabilité et la fluidité de l'expérience utilisateur. Actuellement, les vendeurs attribuent manuellement des catégories aux articles, ce qui peut être peu fiable.

## Objectif du Projet

- Automatiser la classification des articles en différentes catégories.
- Améliorer l'expérience utilisateur pour les vendeurs et les acheteurs.
- Préparer le système pour un passage à l'échelle.

## Étapes du Projet

### 1. Analyse Exploratoire

- Collecte et nettoyage des données.
- Prétraitement des données textuelles et images.
- Extraction des caractéristiques pertinentes pour la classification.

### 2. Étude de Faisabilité

- **Texte** : Utilisation de Bag of Words, Word2Vec, BERT, et USE pour le traitement des descriptions.
- **Image** : Approches SIFT et CNN pour l'extraction de caractéristiques.
- Évaluation des performances des différentes approches avec l'Indice Rand Ajusté (ARI).

### 3. Classification Supervisée

- Implémentation de modèles CNN avec VGG16.
- Test de différentes configurations de datasets et techniques de data augmentation.
- Sélection de la meilleure approche basée sur l'accuracy et le temps de calcul.

### 4. Test de l’API

- Paramétrage du code Python sur RapidAPI pour la collecte de données.
- Transformation des données en DataFrame et exportation en CSV.
- Respect des principes du RGPD lors de la manipulation des données.

## Résultats

- Meilleure performance de classification avec Word2Vec pour les textes.
- Utilisation de CNN pour une extraction efficace des caractéristiques d'images.
- Recommandation d'utiliser un embedding dédié pour ouvrir de nouvelles catégories.

## Livrables

- [Pham-Van_Yann_1_pretraitement_feature_extraction_faisaibilite_072023.ipynb](https://github.com/Bruce2Cluny191/Projet6-Classifiez_automatiquement_des_biens_de_consommation/blob/main/Pham-Van_Yann_1_pretraitement_feature_extraction_faisaibilite_072023.ipynb) : Un notebook d'Analyse des données et extraction des caractéristiques.
- [Pham-Van_Yann_2_notebook_classification_072023.ipynb](https://github.com/Bruce2Cluny191/Projet6-Classifiez_automatiquement_des_biens_de_consommation/blob/main/Pham-Van_Yann_2_notebook_classification_072023.ipynb) : Un notebook d'Essais des différentes approches de classification.
- [Pham-Van_Yann_3_script_Python_072023.ipynb](https://github.com/Bruce2Cluny191/Projet6-Classifiez_automatiquement_des_biens_de_consommation/blob/main/Pham-Van_Yann_3_script_Python_072023.ipynb) : Un notebook de Collecte et traitement des données via l'API.
- [Pham-Van_Yann_4_presentation_072023.pdf](https://github.com/Bruce2Cluny191/Projet6-Classifiez_automatiquement_des_biens_de_consommation/blob/main/Pham-Van_Yann_4_presentation_072023.pdf) : Une présentation Résumé des résultats et recommandations.

## Contact

Pour toute question, veuillez me contacter sur [LinkedIn](https://www.linkedin.com/in/chasseur2valeurs/).
