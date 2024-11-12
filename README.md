# OPC_DATA_ANALYST_PROJET5
Optimisez la gestion des données d'une boutique avec R ou Python

# Analyse des Ventes et des Stocks - Projet BottleNeck

## Aperçu de l'entreprise

![Aperçu du site web](images/DA_projet5.PNG)

## Contexte

Aujourd'hui, je débute ma mission en tant que Data Analyst freelance chez **BottleNeck**, un marchand de vin prestigieux. Mon manager, **Laurent**, m'a présenté l'équipe du service Numérique dans une ambiance conviviale, et m'a expliqué les enjeux de ma première mission.

La gestion des stocks et l’analyse des ventes en ligne sont actuellement limitées par l'absence de connexion entre l'ERP et le site de vente en ligne de BottleNeck. Ma mission est donc d'effectuer un rapprochement entre les deux bases de données, de calculer le chiffre d’affaires pour chaque produit vendu en ligne, et de détecter d’éventuelles erreurs dans les prix des produits.

## Objectifs du Projet

1. **Rapprochement des Exports ERP et Web** : Utiliser les exports de l’ERP et de la plateforme de vente en ligne, ainsi qu'un fichier de liaison créé par une ancienne stagiaire, pour faire correspondre les produits entre les deux bases de données.
   
2. **Calcul du Chiffre d'Affaires par Produit** : Une fois le rapprochement effectué, calculer le chiffre d'affaires par produit, ainsi que le total des ventes réalisées en ligne.

3. **Détection des Valeurs Aberrantes** : Analyser les prix des produits pour identifier les éventuelles erreurs de saisie (valeurs aberrantes) et les représenter graphiquement pour les mettre en évidence.

## Étapes du Projet

### Étape 1 : Rapprochement des Bases de Données

- **Objectif** : Utiliser les fichiers d'export `erp.xlsx` et `web.xlsx`, ainsi que le fichier de liaison `liaison.xlsx`, pour associer chaque produit entre l'ERP et le site de vente en ligne.
- **Détails** :
  - Assurer l'unicité des clés.
  - Vérifier les types de jointures pour s'assurer que chaque produit soit correctement associé.
  - Traiter les éventuelles incohérences dans le fichier de liaison fourni par Sylvie (stagiaire précédente).
  
### Étape 2 : Calcul du Chiffre d'Affaires

- **Objectif** : Calculer le chiffre d'affaires généré pour chaque produit et le total des ventes en ligne.
- **Détails** :
  - Multiplier le prix de vente par le nombre de ventes pour chaque produit.
  - Obtenir le chiffre d'affaires total pour toutes les ventes en ligne.

### Étape 3 : Analyse des Valeurs Aberrantes dans les Prix

- **Objectif** : Identifier les prix de vente anormaux dans la base de données et les représenter graphiquement.
- **Détails** :
  - Utiliser des méthodes statistiques pour détecter les valeurs aberrantes dans les prix (par exemple, Z-score ou IQR).
  - Créer une visualisation pour illustrer ces valeurs aberrantes afin de les présenter lors de la réunion de COPIL.

### Étape 4 : Préparation de la Présentation

- **Objectif** : Préparer une présentation claire et concise pour exposer mes résultats et expliquer les incohérences trouvées.
- **Détails** :
  - Préparer un PowerPoint ou un notebook Jupyter contenant les analyses et visualisations.
  - Sélectionner et présenter au moins cinq incohérences ou valeurs aberrantes détectées.
  - Structurer la présentation de manière à rendre les résultats compréhensibles pour les parties prenantes.

## Détails Techniques

- **Fichiers** :
  - `erp.xlsx` : Export de l’ERP contenant les informations sur les produits (références, prix de vente, stock).
  - `web.xlsx` : Export de la plateforme en ligne contenant le nom, la description, et le nombre de ventes des produits.
  - `liaison.xlsx` : Tableau de liaison entre les `product_id` de l’ERP et les `SKU` de la boutique en ligne.

- **Langage de Programmation** : Python ou R, selon mes préférences. J’ai la possibilité d’utiliser Jupyter Notebook (pour Python ou R) ou R Markdown pour l’analyse.

- **Compétences Utilisées** :
  - Traitement de données avec jointures entre tables.
  - Calculs financiers (chiffre d’affaires).
  - Détection et visualisation des valeurs aberrantes.
  - Communication des résultats par présentation.

## Résumé

Ce projet m'a permis de travailler sur des problématiques de **gestion des stocks** et d'**analyse des ventes** pour un marchand de vin prestigieux. En rapprochant les données de l'ERP et de la boutique en ligne, j'ai pu obtenir une vision claire du chiffre d'affaires par produit, détecter des incohérences dans les prix et préparer une présentation pour les parties prenantes de l'entreprise.
