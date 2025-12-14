# Grenada Mangrove Hydrology and Suitability Mapping

This repository holds the working files for the Grenada Mangrove Hydrology project and the web map used in the Grenada Mangrove Restoration Innovation Hub. The analysis links hydrology, site conditions, and species-specific suitability to support restoration planning across Grenada, Carriacou, and Petite Martinique.

The repository also hosts a published qgis2web map in the `docs` folder. This map is served through GitHub Pages and embedded in the Hub’s “Explore the Map” page.

## Repository structure

- `data/`  
  Input datasets used in the hydrology and suitability analysis.

- `markdowns/`  
  RMarkdown files and scripts documenting data processing, modelling, and map preparation.

- `outputs/`  
  Derived outputs such as tables, figures, and intermediate rasters that feed into reporting and mapping.

- `docs/`  
  Exported web map from QGIS (via the qgis2web plugin). This folder contains:
  
  - `index.html`  
  - `css/`, `js/`, `data/`, `images/`, `legend/`, `markers/`, `webfonts/`

  When GitHub Pages is configured with `main` as the branch and `/docs` as the folder, this directory is served as a static website. The public URL is:

  `https://gaea-conservation-network.github.io/Grenada-Mangrove-Hydrology/`

  The Hub embeds this URL in the “Explore the Map” section so that users can view the interactive suitability map directly on the website.

## Purpose

The combined hydrology analysis and web mapping support:

1. Evaluating ecological site conditions and restoration feasibility.  
2. Visualising species-specific mangrove suitability alongside archaeological constraints.  
3. Providing an open, documented workflow that links spatial analysis to the online Mangrove Restoration Innovation Hub.

Updates to the suitability rasters or symbology can be exported again via qgis2web into `docs/`, and once committed, the live map will update automatically through GitHub Pages.
