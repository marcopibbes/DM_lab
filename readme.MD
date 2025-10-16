# Analisi di Embedding per il Clustering di Testi

Questo progetto confronta l'efficacia di diversi modelli di embedding e algoritmi di clustering per il raggruppamento non supervisionato di testi, basandosi sul paper *"Beyond words: a comparative analysis of LLM embeddings for effective clustering"*.

## 🚀 Scoperta Fondamentale

La qualità e la specializzazione del modello di embedding sono i fattori più critici per il successo del clustering.

La combinazione del modello specializzato **`all-MiniLM-L6-v2`** con l'algoritmo classico **`K-Means++`** ha fornito i risultati migliori (`ARI ≈ 0.90`), dimostrandosi più efficace di modelli generalisti più grandi (`BLOOMZ-3B`) e di metodi di deep clustering più complessi (`CAEclust`, `Deep K-Means`).

## 🛠️ Come Eseguire

### 1. Setup dell'Ambiente

```bash
# Clona il repository
git clone https://github.com/TUO_USERNAME/NOME_REPO.git
cd NOME_REPO

# Crea e attiva un ambiente conda
conda create -n clustering_env python=3.10 -y
conda activate clustering_env