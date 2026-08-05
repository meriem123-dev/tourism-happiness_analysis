# Tourism and Happiness Analysis

## Projet Power BI

Ce projet analyse la relation entre **l'activité touristique** et **le niveau de bonheur** des différents pays et régions du monde.
L'objectif principal est d'identifier des **marchés touristiques à potentiel**, en recherchant des pays combinant un niveau de bonheur relativement élevé avec une fréquentation touristique relativement faible.

---

## Objectifs

Ce dashboard permet notamment de :

- analyser le niveau de bonheur des différents pays ;
- comparer les arrivées touristiques entre les pays et les régions ;
- étudier la relation entre bonheur et tourisme ;
- analyser l'évolution du tourisme au fil des années ;
- identifier des pays présentant un potentiel touristique selon les critères définis ;
- comparer les pays à travers différents indicateurs.

---

## Pages du Dashboard

### 1. Context & Objective

Cette page présente le contexte du projet, les objectifs de l'analyse ainsi que les principaux indicateurs utilisés.

Elle explique également le principe du **Potential Score**, utilisé pour identifier les pays présentant un profil intéressant selon deux critères :

-  un niveau de bonheur élevé ;
-  une fréquentation touristique relativement faible.

---

### 2. Overview

Cette page donne une vue globale des données à travers plusieurs indicateurs et visualisations.

Elle permet notamment d'explorer :

- **Average Happiness Score**
- **Total Tourist Arrivals**
- les différents pays ;
- les **World Region** ;
- les filtres interactifs.

---

### 3. Happiness VS Tourism

Cette page analyse la relation entre le niveau de bonheur et l'activité touristique à l'aide d'un **scatter plot**.

Le graphique utilise :

- **X-axis :** Average Happiness Score
- **Y-axis :** Total Tourist Arrivals
- **Legend :** World Region
- **Details :** Country

Deux lignes médianes permettent de diviser les pays en quatre quadrants.

Le quadrant considéré comme présentant un **potentiel** correspond à :

> **Bonheur élevé + Tourisme relativement faible**

Cette approche permet d'identifier des pays qui pourraient être intéressants à explorer davantage du point de vue touristique.

---

### 4. Potential Markets

Cette page se concentre sur les pays identifiés comme présentant un potentiel selon les critères définis dans l'analyse.

Un pays est considéré comme éligible lorsqu'il possède :

- un **Average Happiness Score supérieur à la médiane** ;
- un **Total Tourist Arrivals inférieur à la médiane**.

Les pays éligibles sont ensuite classés à l'aide du :

- **Potential Score**
- **Potential Rank**

---

### 5. Trends

Cette page permet d'analyser l'évolution des principaux indicateurs au fil des années.

Elle présente notamment l'évolution de :

- **Happiness Score**
- **Tourist Arrivals**
- **Tourism Growth YoY**

L'objectif est d'identifier les principales tendances et évolutions de l'activité touristique et du niveau de bonheur sur la période étudiée.

---

### 6. Country Details

Cette page permet d'approfondir l'analyse d'un pays spécifique grâce à la fonctionnalité **Drillthrough de Power BI**.

Elle permet d'examiner plus précisément :

- **Average Happiness Score**
- **Total Tourist Arrivals**
- **Tourism Growth YoY**
- **Potential Score**
- **Potential Rank**
- l'évolution des indicateurs au fil du temps.

---

##  Potential Score

Le **Potential Score** est un indicateur créé dans le cadre de ce projet afin d'identifier les pays présentant un profil intéressant selon les critères de l'analyse.

Il prend en compte :

- le niveau de **bonheur** ;
- le niveau de **fréquentation touristique**.

L'analyse utilise les **médianes** comme références afin de distinguer les pays présentant :

> **un bonheur élevé et une fréquentation touristique relativement faible.**

Un score élevé indique donc qu'un pays possède un profil correspondant davantage aux critères définis pour les **marchés à potentiel**.

> Le Potential Score est un indicateur créé pour cette analyse et ne constitue pas un classement touristique officiel.

---

##  Principaux indicateurs

Le dashboard utilise notamment :

- **Average Happiness Score**
- **Total Tourist Arrivals**
- **Tourism Growth YoY**
- **Potential Score**
- **Potential Rank**
- **World Region**

---

##  Outils et technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Git & GitHub**
- **TopoJSON** pour la carte personnalisée

---

##  Visualisations

Le dashboard utilise différents types de visualisations :

- KPI Cards
- Scatter Plot
- Maps
- Area Charts
- Tables
- Slicers
- Drillthrough

---

##  Structure du projet

```text
tourism-happiness_analysis/
│
├── PowerBI/
├── maps/
├── data/
└── README.md

```
## Limites de l'analyse

Ce projet a été réalisé dans un objectif **d'apprentissage** et de mise en pratique de Power BI**, notamment à travers Power Query, DAX, la modélisation des données et la création d'un dashboard interactif.

Les résultats présentés ne doivent donc pas être considérés comme une évaluation exhaustive ou une recommandation touristique réelle.

L'analyse repose principalement sur **deux dimensions : le niveau de bonheur et les arrivées touristiques**. Or, le potentiel touristique d'un pays dépend de nombreux autres facteurs, tels que :

- les infrastructures touristiques ;
- les coûts et le pouvoir d'achat ;
- l'accessibilité et les transports ;
- la sécurité ;
- les ressources et attractions touristiques ;
- les conditions économiques ;
- la saisonnalité ;
- les politiques et réglementations ;
- les capacités d'accueil.

Le **Potential Score** est ainsi un indicateur construit spécifiquement pour ce projet afin de mettre en pratique les concepts appris en Power BI. Il permet d'explorer une approche possible de l'identification de marchés à potentiel, mais ne constitue pas un indicateur officiel ni une conclusion définitive sur le potentiel touristique réel d'un pays.
