🌐 Cyber Knowledge Graph (CKG)
A connected graph database for enhanced cybersecurity threat intelligence.

🌟 Overview
This repository contains a Cyber Knowledge Graph (CKG) that integrates various cybersecurity datasets (CVE, CWE, CAPEC, ICS Attack, Mobile Attack) into a unified graph database using Neo4j. This graph-based approach enhances threat intelligence by establishing meaningful relationships between vulnerabilities, exploits, and attack patterns, moving beyond siloed data to a holistic, connected view.

✨ Features
Unified Knowledge Graph: A single, interconnected graph linking multiple cybersecurity datasets.

Neo4j AuraDB: Utilizes a powerful cloud-native graph database for efficient querying and real-time visualization.

Automated Data Import: Scripts for converting and importing diverse datasets into the graph with ease.

Graph Analytics & Threat Detection: Leverage the power of relationships to uncover complex attack paths and detect threats more effectively.

Querying & Visualization: Seamless integration with Neo4j Browser and APIs for powerful data exploration.

🛠️ Technologies Used
Technology

Description

Python

For data processing, cleaning, and integration scripts.

Neo4j AuraDB

The cloud-based graph database hosting the CKG.

Cypher

The declarative graph query language used for querying and analyzing relationships.

Pandas & NetworkX

Libraries for efficient data manipulation and graph analysis.

📂 Repository Structure
import_data.py: A Python script to automate the process of importing cybersecurity datasets into the Neo4j database.

graph_queries.cypher: A collection of useful Cypher queries to help you get started with analyzing the graph.

data/: A directory containing raw and processed cybersecurity datasets.

.env: (Example) File to securely store Neo4j connection credentials. Note: This file is intentionally excluded for security.

💡 How to Contribute
We welcome contributions! Please feel free to open an issue or submit a pull request if you find a bug or have an idea for an improvement.
