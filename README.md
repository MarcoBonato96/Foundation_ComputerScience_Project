# Foundation_ComputerScience_Exam_Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
  https://colab.research.google.com/github/MarcoBonato96/Foundation_ComputerScience_Project/blob/main/Exam_Project_MarcoBonato_def_version.ipynb
)
![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![Status](https://img.shields.io/badge/status-complete-brightgreen.svg)
[![Last commit](https://img.shields.io/github/last-commit/MarcoBonato96/Foundation_ComputerScience_Project.svg)](https://github.com/MarcoBonato96/Foundation_ComputerScience_Project/commits/main)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](#license)

> **One‑liner.** Analisi del dataset *Trending YouTube* per rispondere a richieste di aggregazione temporale/tag/categoria, con pulizia dati, bucketing a 10 minuti e statistiche per paese, tag e categoria.

---

## Indice
- [Panoramica](#panoramica)
- [Dataset](#dataset)
- [Requisiti & Esecuzione](#requisiti--esecuzione)
- [License](#license)

---

## Panoramica
Questo progetto realizza un’analisi esplorativa e aggregata dei video di tendenza su YouTube per il corso **Foundations of Computer Science 2025–2026 (Data Science) – Università degli studi di Milano‑Bicocca**.  
Obiettivi principali:
- Unificare i CSV dei diversi paesi e normalizzare i campi (inclusa la colonna `country`).
- Gestire tag multipli, like/dislike mancanti, e categorie da file JSON per **paese**.
- **Bucket** temporali di 10 minuti con `dt.floor('10min')` per calcoli di *views/like/dislike* per intervallo.
- Statistiche per **tag** (occurrence e #video unici), **(tag,country)**, **(month,country)**, e **categorie** non assegnabili.

---

## Dataset
- Fonte: **Trending YouTube** (link diretto): [Here](https://drive.google.com/drive/folders/1u7fUnvgOfMW12ZSNsE4lfmq5et5aeARH?usp=sharing) 
- File JSON delle categorie per paese: integrati (RU, US, MX, KR, JP, FR, IN, CA, GB, DE).
- **Nota etica**: i dati sono pubblici per fini didattici; nessuna informazione personale sensibile è trattata.

---

## Requisiti & Esecuzione

### Apri direttamente il notebook
[![Apri in Colab](https://colab.research.google.com/assets/colab-badge.svg)](
  https://colab.research.google.com/github/MarcoBonato96/Foundation_ComputerScience_Project/blob/main/Exam_Project_MarcoBonato_def_version.ipynb
)
---
