---

# New Jersey Youth Football GIS Research Project

## Project Overview

This project uses Geographic Information Systems (GIS) to map community youth football organizations throughout New Jersey.

Community youth football organizations give children opportunities to participate in organized football outside of their schools. These organizations often operate through local leagues and community programs.

The purpose of this research is to better understand where these organizations are located and how geographic information could support future planning and coordination.

## What Is NJYASA?

The New Jersey Youth and Amateur Sports Association (NJYASA) is a proposed statewide organization I am developing as part of a larger public administration research project.

The concept is partly inspired by the New Jersey State Interscholastic Athletic Association (NJSIAA), which helps organize high school athletics through a common statewide structure.

NJYASA would explore a similar approach for community youth and amateur sports, with voluntary participation by local organizations.

My larger research also explores whether NJYASA could develop partnerships with the New Jersey Department of State, Department of Children and Families, and Department of Community Affairs.

These partnerships are proposals for further research, not existing agreements.

## PS0 Research Question

Where are community youth football organizations located throughout New Jersey, and how could this geographic information help with the early planning and development of NJYASA?

## Research Data

The research inventory contains 265 documented community youth football organizations.

For PS0, 264 organizations are included in the geographic map. One organization, P181, is excluded pending additional organization verification.

Each mapped point represents the recorded home-field location of one organization, not the location of every participating athlete.

The dataset was prepared through earlier research involving youth football leagues, local organizations, field addresses, geographic coordinates, and location verification.

**Research dataset:**

[PS0 Youth Football Locations CSV](PS0_NJ_Youth_Football_Locations_2026.csv)

**Official geographic data:**

- [New Jersey County Boundaries](https://services2.arcgis.com/XVOqAjTOJ5P6ngMu/arcgis/rest/services/NJ_Counties_3424/FeatureServer/0)
- [New Jersey Municipal Boundaries](https://services2.arcgis.com/XVOqAjTOJ5P6ngMu/ArcGIS/rest/services/NJ_Municipal_Boundaries_3424/FeatureServer/0)

## Reproducing the Map

The PS0 notebook uses Python and Google Colab.

To reproduce the map:

1. Open [PS0 — NJ Youth Football GIS Reproducible Notebook](PS0_NJ_Youth_Football_GIS_Reproducible.ipynb).
2. Open the notebook in Google Colab.
3. Select **Runtime → Run all**.
4. The notebook will download its geographic data from public online sources and generate the New Jersey youth football map.

Access to my personal Google Drive is not required.

## Research Limitations

This inventory is not guaranteed to contain every active community youth football organization in New Jersey.

Some geographic records also have verification limitations. These are documented in the research dataset. For example, P172 has a provisional geographic classification, while P181 is excluded from the primary analysis.

The map shows documented home-field locations. It does not establish participation levels, service areas, transportation access, or whether communities have sufficient youth sports opportunities.

The published CSV is a prepared research dataset. The original organization research, geocoding, and verification process was conducted separately and is not fully reproduced in the PS0 notebook.

## Research and Code Assistance

This research project was developed using Python, Google Colab, GeoPandas, Matplotlib, and publicly available geographic information.

ChatGPT was used to assist with Python code development, troubleshooting, notebook organization, documentation, and map presentation. The code and resulting geographic data were reviewed and tested as part of the project.

## Future Research

Future assignments will build on this geographic foundation by examining additional information relevant to statewide youth sports planning, government coordination, and the possible development of NJYASA.

---
