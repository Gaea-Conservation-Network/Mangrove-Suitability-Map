# Grenada Mangrove Hydrology and Suitability Mapping

This repository hosts the published suitability analysis and interactive map for the Grenada Mangrove Restoration Innovation Hub. The analysis links hydrology, site conditions, and species-specific suitability to support restoration planning across Grenada, Carriacou, and Petite Martinique.

The `docs` folder is served through GitHub Pages and embedded in the Hub's "Explore the Map" page.

## Repository structure

- `docs/`  
  Published outputs served via GitHub Pages:
  
  - `Mangrove-Suitability-Analysis.html`  
    The rendered R Markdown document explaining the modelling approach, variable selection, and results.
  
  - `MangroveSuitabilityInteractive.html`  
    The interactive Leaflet map showing species combination suitability across Grenada's coastal zone.
  
  - `MangroveSuitabilityInteractive_files/`  
    Supporting files for the interactive map.

When GitHub Pages is configured with `main` as the branch and `/docs` as the folder, this directory is served as a static website. The public URL is:

`https://gaea-conservation-network.github.io/Grenada-Mangrove-Hydrology/`

The Hub embeds these pages in the "Explore the Map" section so that users can view the interactive suitability map and read the methods documentation directly on the website.

## Purpose

The suitability analysis and web mapping support:

1. Evaluating ecological site conditions and restoration feasibility.  
2. Visualising species-specific mangrove suitability across Grenada's coastal zones.  
3. Providing transparent documentation of the modelling approach for practitioners and researchers.

Updates to the analysis or maps can be re-rendered and committed to `docs/`. The live pages will update automatically through GitHub Pages.