# Análisis de Dengue en Argentina 2021-2022 

By: Adolfo C. De Boeck.

Version: 0.1.0

En este proyecto se analízan diferentes variables según los registros oficiales del sistema nacional de vigilancia de la salud. 

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x
- Optional [Mamba](https://mamba.readthedocs.io/en/latest/)

## Create environment

```bash
conda env create -f environment.yml
activate análisis_de_dengue_en_argentina_2021_2022
```

or 

```bash
mamba env create -f environment.yml
activate análisis_de_dengue_en_argentina_2021_2022
```

## Project organization

    análisis_de_dengue_en_argentina_2021_2022
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        └── README.md          <- The top-level README for developers using this project.

---
Project created for demonstration purposes for the course "[Personalización Avanzada de Entorno para ciencia de Datos]()" by [Platzi](https://platzi.com/) - [@jvelezmagic](https://jvelezmagic.com/).
