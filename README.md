# TP3 — RAG Multimodal Agentique

Activité pratique N°3 — Mohamed YOUSSFI

## Objectif
Développer un système RAG multimodal capable d'extraire les textes et les images du PDF **Attention Is All You Need**, de les indexer dans ChromaDB et de les interroger avec un agent IA.

## Avancement
- [x] Étape 1 : Extraction PDF
- [x] Étape 2 : Embeddings CLIP
- [x] Étape 3 : Indexation ChromaDB
- [x] Étape 4 : Recherche multimodale
- [x] Étape 5 : Retriever Tool
- [x] Étape 6 : Agent ReAct avec LangGraph
- [x] Étape 7 : Tests

Le notebook principal est [TP3_RAG-Multi-Modal-Agentique.ipynb](./TP3_RAG-Multi-Modal-Agentique.ipynb). Les fichiers générés sont placés dans `resultats_pdf/`, ignoré par Git.

## Utiliser Gemini

Copier `.env.example` vers `.env`, puis renseigner `GOOGLE_API_KEY`.
La clé est chargée automatiquement par le notebook et le fichier `.env` n'est pas versionné.
