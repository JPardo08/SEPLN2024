# SEPLN PhD Symposium 2024 – Automatic Medical Knowledge Graph Construction

Welcome to the repository for the **PhD Symposium 2024** submission by **Joel Pardo-Ferrera**, titled **"Automatic Medical Knowledge Graph Construction"**. This repository contains the essential materials presented at the symposium.

## Repository Structure and Files
- **Paper**: `SEPLN_PHDSympos_2024_Joel_pardo_ferrera2.pdf`
  - This is the full paper submitted for the symposium, outlining the methodology, objectives, and key findings of the research.
  
- **Presentation**: `SEPLN_Sympos_definitiva.pdf`
  - A slide deck summarizing the key points of the research, designed for a 3-minute oral presentation at the symposium.

- **Poster**: `PhD_SEPLNSympos2024_jpardo_definitivo.pdf`
  - A poster highlighting the main contributions and findings of the research, used for the symposium's poster session.

## Abstract
Knowledge Graphs are crucial for structuring and integrating large amounts of data, improving decision- making and data interoperability, especially in the healthcare domain. This PhD thesis aims to implement a unified end-to-end framework for building a cross-lingual KG for English and Spanish in the healthcare sector using NLP techniques. Addressing the reliance on traditional methods in KG construction and the limited non-English language resources, this work seeks to refine the information extraction process within unstructured medical texts and facilitate the (re)use of existent ontologies (schema to represent the real-world).


## Research Focus
Developing an automated framework to generate domain-specific KGs for the electronic health sector, aimed at assisting medical professionals in the decision-making process.


1. **Preliminary Health Domain Analysis and Planning**:
- Initial analysis by gathering requirements from healthcare professionals and analyzing Electronic Health Records (EHRs) authored by them. 
- This stage is critical to understanding the data's structure and developing methodologies for extracting knowledge from unstructured clinical text.

2. **Ontology Review, Selection, and Adaptation:**
- Review and select existing ontologies within the health domain, aligning them with the requirements identified in the preliminary analysis. 
- The most suitable ontology is chosen, and any gaps in addressing specific health domain needs are identified. 
- The selected ontology is adapted (if it is needed) to model the entire problem comprehensively. 
- This step ensures that the constructed Knowledge Graph (KG) will be interoperable and contextually accurate for the medical domain.

3. **Technological Framework Development:**
- Fine-tuning Large Language Models (LLMs) to incorporate the ontology knowledge, enabling the model to identify relevant entities and relationships within the clinical text. 
- Structure the extracted data into RDF triplets, forming a formal and usable Knowledge Graph (KG).

4. **Evaluation Framework Development:**
- Evaluation framework to assess the entire workflow and the performance of individual IE tasks. 
- A test environment is created where healthcare professionals can input real-world cases, allowing for the automatic extraction and validation of KGs in decision-making scenarios. 
- This ensures the practical applicability and accuracy of the KG in assisting healthcare professionals.

## Funding
This work has been funded by INESData (Infraestructura para la INvestigación de ESpacios de DAtos distribuidos en UPM) project, from Ministerio para la Transformación Digital y de la Función Pública (PRTR, UNICO I+D CLOUD, EU NextGeneration).


## Installation
If you'd like to explore the paper and materials, simply clone the repository:

```bash
git clone https://github.com/JPardo08/SEPLN2024.git
