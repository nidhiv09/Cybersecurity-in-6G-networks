Overview

This repository contains a Cyber Knowledge Graph (CKG) that integrates various cybersecurity datasets (CVE, CWE, CAPEC, ICS Attack, Mobile Attack) into a connected graph database using Neo4j. This graph-based approach enhances threat intelligence by establishing meaningful relationships between cybersecurity vulnerabilities, exploits, and attack patterns.

Features

Unified Knowledge Graph connecting CVE, CWE, CAPEC, ICS Attack, and Mobile Attack.

Neo4j Graph Database for efficient querying and visualization.

Automated Data Import using CSV/JSON conversion.

Graph Analytics & Threat Detection leveraging relationships in cybersecurity datasets.

Support for Querying & Visualization via Neo4j Browser and APIs.

Technologies Used

Python (Data Processing & Integration)

Neo4j AuraDB (Graph Database)

Cypher Query Language (For querying relationships)

Pandas & NetworkX (Data processing & graph analysis)

Files

import_data.py - Imports cybersecurity datasets into Neo4j.

graph_queries.cypher - Sample Cypher queries for analysis.

data/ - Contains raw and processed cybersecurity datasets.

.env - Stores Neo4j connection credentials (not included for security).
