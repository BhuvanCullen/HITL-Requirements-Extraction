# Automated Requirements Traceability & Classification Pipeline

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A robust machine learning and rule-based pipeline designed to extract, classify, and map system requirements across abstraction levels (L1–L4) to ensure structural continuity and minimize scope drift.

---

## Project Overview
Managing requirements manually across large-scale technical specifications is prone to human error, information loss, and traceability gaps. This repository contains the source code and evaluation scripts for an automated requirements engineering workflow that combines:
* **Rule-Based Heuristics:** Regular expression parsing and pattern matching for structured extraction.
* **Supervised Machine Learning:** Comparative evaluation of classifiers (SVM, Random Forests, Decision Trees) and vectorization techniques (TF-IDF/BoW) for automated requirement categorization.
* **Traceability Mapping:** Maintaining structural linkages from high-level objectives down to granular engineering specifications.

---

## Repository Structure
```text
├── data/                  # Input datasets and raw requirements documents
├── src/
│   ├── extraction/        # Rule-based parsing and RegEx extraction scripts
│   ├── preprocessing/     # Text cleaning, tokenization, and vectorization (TF-IDF)
│   ├── models/            # Training and evaluation scripts (SVM, RF, Decision Trees)
│   └── traceability/      # Requirement mapping and linking logic
├── notebooks/             # Exploratory data analysis and model prototyping
├── outputs/               # Generated reports, evaluation matrices, and exported links
├── requirements.txt       # Project dependencies
└── README.md
