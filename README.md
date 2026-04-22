# Burundi-inflation-data
Script Python permettant l'extraction, le nettoyage et la visualisation graphique des données de la Banque Mondiale concernant le Burundi (Focus actuel : Inflation).
# Burundi Economic Data Pipeline (World Bank)

# Contexte
Comprendre l’évolution de l’inflation au Burundi est essentiel pour les ménages et les ONG opérant dans un environnement économique fragile. Ce projet transforme des données brutes en signaux lisibles pour la prise de décision.

## 📌 Description
Ce projet automatise l'extraction, le nettoyage et la visualisation des indicateurs macroéconomiques du Burundi à partir des données brutes de la Banque Mondiale. L'objectif est de transformer des fichiers CSV complexes en graphiques exploitables pour le monitoring économique.

## 🛠️ Stack Technique
* **Langage :** Python 3.x
* **Librairies :** * `Pandas` : Manipulation et nettoyage de structures de données.
    * `Matplotlib` : Génération de visualisations graphiques.
    * `NumPy` : Support pour les calculs numériques.

## ⚙️ Fonctionnalités du Pipeline
1. **Ingestion de données :** Chargement des exports CSV de la World Bank.
2. **Nettoyage Structurel :** Élimination des métadonnées hors-tableau et gestion des valeurs manquantes via `dropna`.
3. **Extraction par Motifs (Pattern Matching) :** Isolation dynamique d'indicateurs (ex: Inflation) par filtrage de chaînes de caractères.
4. **Visualisation :** Tracé automatique de courbes d'évolution temporelle.

## 🚀 Utilisation
1. Placer le fichier CSV de la Banque Mondiale dans le répertoire racine.
2. Exécuter le script principal pour générer les graphiques.

## Résultats
L’analyse révèle une tendance haussière de l’inflation au Burundi sur la période 1998–2024, visualisée sous forme de courbes temporelles générées automatiquement.
