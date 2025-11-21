# 📰🔗 Financial News Knowledge Graph

This project downloads **financial news** using a News API and automatically builds a **knowledge graph** using **LLMs + Neo4j**.

## 🚀 What This Project Does
- Pulls financial news  
- Extracts entities & relationships with an LLM  
- Cleans and converts extracted triplets  
- Builds a knowledge graph in Neo4j  
- Supports natural language → Cypher querying  

## 📦 Pipeline Overview
### 1️⃣ Data Preprocessing  
Clean and split raw news text into usable segments.

### 2️⃣ Entity & Relationship Extraction  
Use an LLM to generate structured triplets such as:  
`Company A —acquires→ Company B`

### 3️⃣ Data Cleaning  
Fix formatting issues, remove invalid records, and standardize outputs.

### 4️⃣ Graph Construction  
Import triplets into Neo4j using Py2neo and visualize the graph.

### 5️⃣ Natural Language Query  
Convert English questions into Cypher queries to explore the graph.

---
