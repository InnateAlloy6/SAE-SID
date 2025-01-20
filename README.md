# SAE-SID

# Analyse des tendences d'achats des jeux videos en ligne 

## Description du Projet 
Ce projet vise à analyser les comportements des consommateurs dans le domaine du commerce en ligne de jeux videos afin de répondre à la problématique :   

**”Quelle est la rentabilité des jeux vidéo selon les plateformes (PC, consoles, mobile) et quels sont les facteurs qui influencent cette rentabilité ?”** 
L’objectif est de fournir des insights détaillés en exploitant diverses sources de données, en intégrant ces données dans un système d’information décisionnel (SID), et en créant des tableaux de bord visuels pour une prise de décision éclairée.

## Contenu
### 1. Sources de Données 
Nous utilisons les datasets suivants : 
- **Video Game Sales Dataset Updated -Extra Feat** : Données sur les ventes de jeux vidéo. 
- **Top 1500 Games on Steam by Revenue (09-09-2024)** : Informations sur les jeux les plus populaires. 
- **Epic Games Store Data** : Statistiques de ventes et avis des utilisateurs. 

Ces données sont accessibles via des plateformes comme [Kaggle](https://www.kaggle.com). 

### 2. Modèle des Données 
Un modèle structuré permet d’intégrer et de lier les données de différentes sources : 
- **Organisation par tables** : Chaque source est représentée dans des tables distinctes. 
- **Clés communes** : Liens entre les tables basés sur des champs partagés (ID produit, région, catégorie, etc.). 

### 3. Processus ETL (Extraction, Transformation, Chargement) 
- **Granularité** : 
  - Plateforme spécifique: Séparer les ventes selon les plateformes spécifiques pour comprendre comment chaque plateforme évolue.
  - Genre de jeu: Catégoriser les jeux par genre pour étudier les préférences des joueurs par plateforme.

- **Mise à jour périodique** : Alimentation mensuelle du SID. 

### 4. Tableau de Bord 
Les analyses incluent : 
- Répartition des ventes par produit. 
- Analyse des revenus par plateforme. 
- Étude de la satisfaction client. 
- Répartition des consommateurs par tranche d’âge. 

## Auteurs 
- [Matteo Cai]()
- [Diego Casas](https://github.com/InnateAlloy6) 
- **[Leo Jean Unite](https://github.com/TheColonel92)** 

Projet réalisé dans le cadre du module **[SF23Y020 – Intégration de données dans un Datawarehouse](https://up75-my.sharepoint.com/:f:/g/personal/leo-jean_unite_etu_u-paris_fr/EqiZWGWtvFpEk5rG8xhknTABkemmmbbd0obIYjkIXZsMcg?e=Rxe9zh)**. 

## Usage 
1. **Installation** : Cloner le dépôt et s’assurer que les dépendances nécessaires sont installées. 
2. **Exécution** : Suivre les instructions pour exécuter les scripts ETL et visualiser les tableaux de bord. 

## License 
Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d’informations. 

------------------------------------------------------------------------------------------------
# 04/12/2024 - Création d'un dossier commun Github
Importation des documents [Onedrive](https://up75-my.sharepoint.com/:f:/g/personal/leo-jean_unite_etu_u-paris_fr/EqiZWGWtvFpEk5rG8xhknTABkemmmbbd0obIYjkIXZsMcg?e=Rxe9zh) ---> Github

## Modification:
- Changement de problématique
  - Quels sont les plus grands consommateurs de produits en ligne ?
- Changelent de données:
  - [Video Game Sales Dataset Updated -Extra Feat](https://www.kaggle.com/datasets/ibriiee/video-games-sales-dataset-2022-updated-extra-feat)
  - [Top 1500 games on steam by revenue 09-09-2024](https://www.kaggle.com/datasets/alicemtopcu/top-1500-games-on-steam-by-revenue-09-09-2024)
  - [Epic Games Store](https://www.kaggle.com/datasets/ramjasmaurya/epic-games-store)
- Rédaction du [Rapport 3](https://github.com/InnateAlloy6/SAE-SID/blob/main/Rapport/CommerceEnLigne_Rapport_3_CAI_CASAS_UNITE.pdf)

# 08/01/2025 - Continuation du projet
- Rassemblement des données
- Mise en place des données sous PowerBI
  - Conversion des données incohérentes 
  - Ajustement en graphique

# 15/01/2025
- [Description du Rapport Finale](https://up75-my.sharepoint.com/:b:/g/personal/leo-jean_unite_etu_u-paris_fr/EXwHu-M2d-dCquvAS-JFbvsBYkcOgmbBrqF1TFYAluA6bg?e=IQDPtD)
- PowerBI
  - Importation des données
    - EPIC
      - Correction de divers variables
        - Date
        - Prix
          - Conversion
  - STEAM
    - Remplacement de "." par "," pour les valeurs décimales
    - Changement de type de divers variable: texte -> numérique
      - Arrondie des valeurs de variable numérique (ex: AveragePlayTime)
  - Video Games
    - Changement de type pour les dates (Texte -> Date)
    - Remplacement de "." par "," pour les valeurs numériques
- Mise en place du modéle de données en "étoile" pour les ventes
  
# 20/01/2025
- Rédaction du rapport rapport finale
- Mise en place du modéle de données en "étoile" pour les notations
- Finalisation de la mise en place des données
  - Mise en place des visualisations
