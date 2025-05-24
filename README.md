# Stras1920 🗺️

**Stras1920** est une carte interactive développée dans le cadre d’un mémoire en histoire (informatique appliquée à l’histoire), visant à explorer l’urbanisme et l’économie de la boisson à Strasbourg en 1920. Elle permet de consulter, filtrer et analyser spatialement différents types d'établissements liés à la production et à la distribution d'alcool. Les données produites sont ouvertes (CC-BY). Le projet contient donc un dossier data contenant les données, un dossier map contenant une carte interactive réalisée avec MapLibre et Astro, puis Stras1920.ipynb est un notebook Google Colab dans lequel nous montrons comment nous avons utilisé la librairie Python GeOCR (développé dans le cadre du mémoire) pour extraire les données géospatiales de nos archives historiques de Strasbourg.

##  Fonctionnalités principales

-  **Navigation par mode** :
    - `Consultation` : visualisation individuelle des points avec explorateur de données (Nom, type, adresse).
    - `Cluster` : regroupe les entités proches pour une meilleure lisibilité.
    - `Heatmap` : carte de densité dynamique (rayon ajustable).

-  **Couches de données** :
    - 12 catégories d’établissements (débits de vin, cidreries, brasseries, etc.)
    - Affichage activable par catégorie.

- **Interface claire** :
    - UI avec Astro et TailwindCSS.
    - Infos contextuelles et légendes accessibles.

- **Sources historiques** :
    - Plans vectorisés de 1920.
    - Annuaire d’adresses numérisé.
    - Table de correspondance des rues (Moszberger, 2012).

##  Technologies

- [Astro](https://astro.build/) – Frontend statique
- [MapLibre GL JS](https://maplibre.org/) – Carte interactive
- TailwindCSS – Design rapide et responsive 
- DaisyUI - Components TailwindCSS

##  Installation

```bash
npm install
npm run dev
