# Tatiana Prytkova

Senior Applied AI Scientist / Senior Data Scientist | GenAI, LLM/RAG, Biomedical NLP, Python, Scientific ML 

## Technical Skills
- Retrieval-Augmented Generation pipeline design
- Hybrid search: sparse TF-IDF/BM25-style retrieval plus dense transformer embeddings
- Biomedical NLP and literature search workflows
- FastAPI backend development
- Streamlit dashboard development
- pytest-based automated testing
- Docker and docker-compose deployment
- Python package organization with `src/`, `scripts/`, `tests/`, and `docs/`

- Python for scientific data analysis
- RDKit and cheminformatics
- Molecular docking and virtual screening
- Molecular modeling and protein-ligand interaction analysis
- pandas, NumPy, scikit-learn, matplotlib
- Drug-likeness filtering, scaffold analysis, and ADME data preparation

## Featured Repository


## Selected AI, Biomedical NLP, and Drug Design Projects

### AI Molecule Design Assistant

Open-source cheminformatics and AI-assisted drug-design workflow for triaging generated or user-provided small molecules. The app supports chemical standardization, RDKit descriptor calculation, public chemical identity lookup, biomedical-context evidence using optional BioBERT/PubMedBERT-style embeddings, patent/IP-context evidence using optional PaECTER/patent-BERT-style models, interpretable prioritization, and reproducible report generation.

The workflow is designed for early-stage research triage of generative molecular candidates. IP-context and patent-evidence outputs are used only as computational research signals and do not determine novelty, patentability, freedom to operate, ownership, infringement risk, efficacy, safety, or clinical value.

Live demo: https://ai-molecule-design-assistant.streamlit.app/
Repository: https://github.com/tprytkov/ai-molecule-design-assistant

---

### Biomedical Temporal Knowledge-Graph Memory Agent

Local-first biomedical agent memory system using temporal knowledge-graph facts, synthetic biomedical data, FastAPI, Streamlit, optional Neo4j, and evaluation metrics. The project demonstrates how structured biomedical memory can support retrieval, reasoning, and explainable agent workflows.

Live demo: https://biomed-kg-memory-agent-jqqguacema26da5fdfnk9m.streamlit.app/
Repository: https://github.com/tprytkov/biomed-kg-memory-agent

---

### Biomedical RAG Hybrid Search

Biomedical retrieval-augmented generation prototype combining sparse keyword search, dense embeddings, score fusion, FastAPI endpoints, test coverage, and reproducible local setup. The project demonstrates hybrid retrieval for biomedical question answering and document search.

Live demo: https://biomed-rag-hybrid-search-hmnywnzkx68xjbjkxentmw.streamlit.app/
Repository: https://github.com/tprytkov/biomed-rag-hybrid-search

---

### Drug Design Data Analysis Scripts

Python scripts for computational drug discovery workflows, including RDKit QED/SA filtering, docking-result analysis, scaffold-diversity analysis, interaction-fingerprint analysis, molecular-property calculations, and SwissADME batch preparation.

Repository: rdkit

