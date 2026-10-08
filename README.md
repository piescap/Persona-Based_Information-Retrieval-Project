# Persona-Based Information Retrieval Project

<p align="center">21 June 2025</p>

## Overview

The **final project** for the course **Information Retrieval and Recommender Systems**, held by **Professor Gabriella Pasi**, **Professor Georgios Peikos**, and **Professor Pranav Kasela**.

The project explores **persona-based information retrieval** on the **ANTIQUE** dataset, investigating how different user personas (novice vs. expert) and query reformulation strategies affect retrieval performance.

The main goal is to compare a traditional lexical retrieval approach, **BM25**, with a **Neural Reranking** model, and to evaluate how **query expansion** and **persona-driven query reformulation** (using **Google Gemini**) impact retrieval effectiveness.

---

## Objectives

- Load and preprocess the ANTIQUE test collection (queries, documents, and relevance judgments)
- Perform exploratory data analysis on query/response distributions and word frequencies
- Implement and evaluate a **BM25** baseline retrieval system
- Implement and evaluate a **Neural Reranking** approach
- Use **Google Gemini** for LLM-powered **query expansion** and **persona-based query reformulation** (novice and expert)
- Compare retrieval performance across all configurations using **Precision, Recall, MAP, and nDCG**

---

## Project Structure

The project is organized into the following main phases:

- **Data Loading and Cleaning** — loading the ANTIQUE dataset (queries, documents, qrels) and preparing binary relevance judgments
- **Exploratory Data Analysis** — analyzing query response distributions, response/query lengths, and top word frequencies
- **Phase I** — Baseline retrieval with BM25 and Neural Reranking, followed by evaluation
- **Phase II** — LLM-assisted query enhancement using three strategies:
  - **Query Expansion** — expanding queries with additional context via Gemini
  - **Query Reformulation: Novice** — rewriting queries as a novice user would
  - **Query Reformulation: Expert** — rewriting queries as an expert user would
- **Final** — Comprehensive comparison of all retrieval configurations

--.

## Repository Contents

- `CODE_Course_Project.ipynb` — complete implementation and analysis
- `datasets_phase2_expanded_novice_expert/` — query datasets for Phase II (expanded, novice, and expert reformulations)
- `REPORT_Course_Project.pdf` — detailed project report
- `PPT_Course_Project.pdf` — project presentation
- `requirements.txt` — Python dependencies
