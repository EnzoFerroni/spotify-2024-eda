# Spotify 2024 Exploratory Data Analysis

[![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Exploratory data analysis of the most-streamed Spotify songs of 2024, looking for the patterns behind a song's success on the platform.

## Table of Contents

- [About](#about)
- [Dataset](#dataset)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Presentation](#presentation)
- [Team](#team)
- [License](#license)

## About

Applied Project I of the Data Science program at Universidade Presbiteriana
Mackenzie (2025, first semester). Over four stages the team wrote a project proposal,
ran an exploratory data analysis in Python, built a data storytelling outline and
recorded a final presentation. Documents and the notebook are in Portuguese.

## Dataset

[Most Streamed Spotify Songs 2024](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024)
(Kaggle). Each row is a track with its Spotify streams and popularity alongside
metrics from other platforms (YouTube, TikTok, Apple Music, Shazam and more). A copy
is stored in [`data/`](data/).

## Repository Structure

```
├── data/        Dataset (CSV)
├── notebooks/   Final exploratory data analysis notebook
├── entregas/    Deliverables for each stage (etapa1 to etapa4)
├── docs/        Course guidelines
└── Cronograma.md  Project schedule
```

## Getting Started

Open the notebook directly on GitHub to read the results, or run it locally:

```bash
git clone https://github.com/EnzoFerroni/spotify-2024-eda.git
cd spotify-2024-eda
pip install pandas matplotlib seaborn jupyter
jupyter notebook notebooks/
```

The CSV is read with a Latin-1 encoding because the source file is not valid UTF-8.

## Presentation

- Video: [youtu.be/M3iHz7ZV6ig](https://youtu.be/M3iHz7ZV6ig)
- Final report: [`entregas/etapa4/ProjetoAplicadoI.pdf`](entregas/etapa4/ProjetoAplicadoI.pdf)
- Storytelling: [`entregas/etapa4/Storytelling.pdf`](entregas/etapa4/Storytelling.pdf)

## Team

| Name | GitHub |
| --- | --- |
| Daniel dos Santos da Silva | [@Daniels-S](https://github.com/Daniels-S) |
| Enzo Ferroni | [@EnzoFerroni](https://github.com/EnzoFerroni) |
| Hudson Carvalho de Jesus | |
| Vinícius de Souza Sabiá | [@viniciussabia](https://github.com/viniciussabia) |

## License

Code and documents are released under the [MIT License](LICENSE). The dataset belongs
to its Kaggle author and is redistributed under its original terms.
