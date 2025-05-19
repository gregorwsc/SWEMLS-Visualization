# SWEMLS Visualizer

The **SWEMLS Visualizer** is an interactive tool that visualizes metadata and workflows of hybrid AI systems described in the [Semantic Web and Machine Learning Systems Ontology (SWEMLS)](https://semsys.ai.wu.ac.at/sites/swemls-kg/). It supports semantic querying, pattern-based workflow analysis, and generates draw.io-compatible XML files for system visualization.

>  **Try it live via Binder:**  
> [![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gregorwsc/SWEMLS-Visualization/main?urlpath=voila/render/Binder_Test.ipynb&build=1)

---

##  Features

-  Load example RDF data or upload your own `.ttl` file
-  Query systems using SPARQL
-  Detect system patterns and generate workflows
-  Choose between template-based or automatic layout generation
-  Export draw.io-compatible `.xml` visualizations
-  Download enhanced metadata files

---

## 📖 User Guide

### 1. Select your data source
- Use the included example file (400+ hybrid AI systems), or
- Upload your own RDF/TTL file.
- Click **Continue** to proceed.

### 2. Search for a system
- Enter a custom SPARQL query to find a system.
- Click **Run Query**, then **Confirm Selection**.

### 3. Choose a visualization method
- If a known pattern is linked:
  - Use a predefined template **or**
  - Generate the workflow using the automatic layout algorithm.
- If no pattern is linked:
  - Upload a valid pattern TTL file and click **Continue with Uploaded Pattern**.

### 4. Download your visualization
- Once generated, click the provided download link.
- The downloaded `.drawio` or `.xml` file can be imported directly into [draw.io](https://app.diagrams.net/) or any compatible tool.

---
