# 🌐 Cyber Knowledge Graph (CKG)
A connected graph database for enhanced cybersecurity threat intelligence.

---

## 🌟 Overview
This repository contains a **Cyber Knowledge Graph (CKG)** that integrates various cybersecurity datasets (**CVE, CWE, CAPEC, ICS Attack, Mobile Attack**) into a unified graph database using **Neo4j**.  
This graph-based approach enhances threat intelligence by establishing meaningful relationships between vulnerabilities, exploits, and attack patterns — moving beyond siloed data to a **holistic, connected view**.

---

## ✨ Features
- **Unified Knowledge Graph**: A single, interconnected graph linking multiple cybersecurity datasets.  
- **Neo4j AuraDB**: Cloud-native graph database for efficient querying and real-time visualization.  
- **Automated Data Import**: Scripts for converting and importing diverse datasets with ease.  
- **Graph Analytics & Threat Detection**: Discover complex attack paths and detect threats using relationships.  
- **Querying & Visualization**: Seamless integration with **Neo4j Browser** and APIs for powerful exploration.  

---

## 🛠️ Technologies Used
- **Python** → Data processing, cleaning, and integration scripts.  
- **Neo4j AuraDB** → Cloud-based graph database hosting the CKG.  
- **Cypher** → Declarative graph query language for querying and analyzing relationships.  
- **Pandas & NetworkX** → Libraries for efficient data manipulation and graph analysis.  

---

## 📂 Repository Structure
- `import_data.py` → Automates importing cybersecurity datasets into Neo4j.  
- `graph_queries.cypher` → Collection of useful Cypher queries for analysis.  
- `data/` → Directory containing raw and processed cybersecurity datasets.  
- `.env` → Example file to securely store Neo4j credentials (**excluded for security**).  

---

