# Flew

Application web d'analyse financière, de scoring et d'aide à la décision sur les marchés boursiers.

## Contexte

Ce projet est développé dans un cadre personnel et académique dans le cadre du cursus d'ingénieur en Systèmes Numériques à l'UTT. Il a pour objectif de concevoir de bout en bout un outil logiciel orienté Data et Finance, de la structuration des bases de données jusqu'à l'interface utilisateur, afin de préparer une alternance en IA & IoT.

## Description

Flew combine l'analyse fondamentale, l'analyse qualitative (avantages compétitifs / Moats) et l'analyse technique (indicateurs de marché). L'application s'appuie sur un algorithme de scoring multicritère maison pour évaluer les actions et structurer l'aide à la décision à travers des classements ciblés (Top/Flop).

## Fonctionnalités (MVP)

- Consultation des actions, des entreprises et de leurs données financières.
- Visualisation de graphiques et d'indicateurs techniques (RSI, etc.).
- Dashboard interactif intégrant les recommandations de l'algorithme de scoring.
- Outils de tri, listes de suivi et comparaison sectorielle.

## Stack Technique

- **Langage :** Python
- **Interface graphique :** Streamlit
- **Base de données :** SQLite
- **Traitement et collecte :** Pandas, yfinance

## Architecture du projet

```text
Flew/
├── README.md
├── License.md
├── requirements.txt
├── data/
│   └── flew.db
├── docs/
│   └── cahier_des_charges.docx
├── src/
│   ├── __init__.py
│   ├── app.py
│   ├── database.py
│   └── pipeline/
│       ├── collector.py
│       └── scorer.py
└── assets/
    └── img/


## Pour cloner le dépot :
git clone [https://github.com/MaayZz/Flew.git](https://github.com/MaayZz/Flew.git)
cd Flew

## Installer les dépendances :
pip install -r requirements.txt

## Lancer l'application :
streamlit run src/app.py
 
