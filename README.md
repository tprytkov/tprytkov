# Tatiana Prytkova

Senior Applied AI Scientist / Senior Data Scientist | GenAI, LLM/RAG, Biomedical NLP, Python, Scientific ML 

## Technical Skills

### Scientific AI / Machine Learning
- Biomedical NLP, transformer models, and literature-evidence workflows
- Retrieval-Augmented Generation pipeline design
- Hybrid search: sparse TF-IDF/BM25-style retrieval plus dense transformer embeddings
- ChemBERTa / BioBERT-style model integration for biomedical and molecular analysis
- Model-cache management, offline/local model loading, and model-source transparency
- pytest-based automated testing and reproducible ML pipeline validation

### Cheminformatics and Drug Discovery
- RDKit-based molecular standardization, descriptor calculation, and chemical similarity analysis
- Drug-likeness filtering, ADME/BBB prediction, QED, Lipinski/Veber-style checks
- Molecular docking, virtual screening, and docking-score interpretation
- Synthetic accessibility heuristics and compound prioritization workflows
- Molecular modeling and protein-ligand interaction analysis
- Chemical identity checks, scaffold analysis, and known-compound comparison

### Full-Stack Scientific Software
- FastAPI backend development for scientific and ML workflows
- React/MUI dashboard development for data-rich scientific applications
- Streamlit dashboard development for rapid scientific prototyping
- Persistent run metadata, local JSON manifests, and result-report generation
- Python package organization with `src/`, `tests/`, `docs/`, and modular pipeline structure
- pandas, NumPy, scikit-learn, matplotlib

### Deployment and Engineering
- Git/GitHub project organization and reproducible local setup
- Docker and docker-compose deployment
- Local-first architecture for large model files and scientific compute workflows

## Featured Repository

### MolOptima

MolOptima is a full-stack scientific application for prioritizing AI-generated or user-provided small molecules and connecting top candidates to biopharma intelligence signals.

The application integrates molecular standardization, RDKit descriptors, BBB/ChemBERTa prediction from a local app-managed model cache, synthetic accessibility scoring, optional docking-score input, exact chemical identity checks, local chemical similarity analysis, model/data-source transparency, persistent run summaries, compound detail views, and Markdown report export.

MolOptima is designed as a working scientific software system for early-stage compound evaluation. Computational outputs are screening signals only and do not determine clinical efficacy, safety, patentability, freedom to operate, or legal conclusions.

Repository: https://github.com/tprytkov/moloptima


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

