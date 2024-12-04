# SAE-SID

# Analyse des Comportements d’Achat en Ligne 

## Description du Projet 
Ce projet vise à analyser les comportements des consommateurs dans le domaine du commerce en ligne afin de répondre à la problématique :   

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
- Matteo Cai 
- Diego Casas 
- **Leo Jean Unite** 

Projet réalisé dans le cadre du module **SF23Y020 – Intégration de données dans un Datawarehouse**. 

## Usage 
1. **Installation** : Cloner le dépôt et s’assurer que les dépendances nécessaires sont installées. 
2. **Exécution** : Suivre les instructions pour exécuter les scripts ETL et visualiser les tableaux de bord. 

## License 
Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d’informations. 

----------------
# 04/12/2024 - Création d'un dossier commun Github
Importation des documents [Onedrive](https://up75-my.sharepoint.com/:f:/g/personal/leo-jean_unite_etu_u-paris_fr/El2XBclPkrdEpmYaHk_wLEYB01yCM279p-_sZY6xAgeQFg?e=yeVkkb) ---> Github

## Modification:
- Changement de problématique
