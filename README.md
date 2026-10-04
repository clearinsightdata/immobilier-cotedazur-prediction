# Prédiction des prix immobiliers — Côte d'Azur 2025

## Le problème
Acheteurs et vendeurs immobiliers manquent de données objectives 
pour évaluer un bien sur la Côte d'Azur — un marché très hétérogène 
où les prix varient de 1 à 10 selon la commune et le type de bien.

## La solution
Analyse complète des transactions immobilières réelles 2025 
(source : DVF open data) et modèle prédictif du prix au m² 
par commune, type de bien et surface.

## Résultats clés
- 📊 **27 304 transactions réelles** analysées — Alpes-Maritimes 2025
- 🏆 **Saint-Jean-Cap-Ferrat** — commune la plus chère à 17 736 €/m²
- 🏠 **Les maisons coûtent 27 à 35% plus cher** que les appartements
- 📍 **Nice** — prix médian 4 800 €/m², marché le plus actif (8 645 transactions)
- 🤖 **Modèle prédictif** — estimation du prix total d'un bien

## Exemples de prédictions

| Bien | Surface | Ville | Prix estimé |
|------|---------|-------|-------------|
| Appartement | 60m² | Nice | 296 370 € |
| Maison | 120m² | Cannes | 879 188 € |
| Appartement | 45m² | Antibes | 260 888 € |

## Top communes par prix au m²

| Commune | Prix moyen/m² |
|---------|--------------|
| Saint-Jean-Cap-Ferrat | 17 736 € |
| Eze | 17 361 € |
| Saint-Paul-de-Vence | 16 174 € |
| Cap-d'Ail | 13 356 € |
| Cannes | 11 393 € |
| Nice | 8 854 € |

## Stack technique
- **Python** — Pandas, NumPy, Scikit-learn, Plotly
- **Modèle** — Gradient Boosting Regressor
- **Données** — DVF open data (data.gouv.fr)

## Structure du projet
- data/immobilier_clean.csv — 27 304 transactions nettoyées
- notebooks/01_exploration_dvf.ipynb — Exploration et nettoyage
- notebooks/02_visualisations_carte.ipynb — Visualisations et modèle

---
*Projet réalisé par [ClearInsightdata](https://github.com/clearinsightdata)*