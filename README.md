# AI & SEO / LLM Visibility™ Glossary Dataset

## Overview
This repository provides an open glossary of key terms shaping visibility in the age of AI search.  
It includes structured definitions for concepts such as:

- **AI SEO** – using AI to accelerate research and optimize for AI-driven search.  
- **Generative AI SEO** – making content “answer-ready” for AI Overviews.  
- **LLM SEO** – optimizing eligibility for citation by ChatGPT, Gemini, Claude, Perplexity, and Grok.  
- **Semantic SEO** – entity-first structuring of content.  
- **Answer Engine Optimization (AEO)** – winning direct AI/Google answers.  
- **Generative Engine Optimization (GEO)** – optimizing for multi-paragraph AI-generated responses.  
- **ChatGPT SEO** – eligibility for OpenAI model surfacing.  
- **AI Visibility** – how often your brand surfaces in AI answers.  
- **LLM Visibility™** – our trademarked framework for measuring and improving surfacing across large language models.  

The dataset is maintained by **Matthew Bertram** and **EWR Digital**, and mirrored across three hubs:  

- [MatthewBertram.com](https://www.matthewbertram.com/) → canonical definitions  
- [EWRDigital.com](https://www.ewrdigital.com/) → applications in client strategy  
- [BestSEOPodcast.com](https://www.bestseopodcast.com/) → discussions and amplification  

---

## Contents
- `data/glossary.csv` — clean tabular format.  
- `data/glossary.json` — JSON array for programmatic use.  
- `data/jsonld/` — per-term JSON-LD files using Schema.org `DefinedTerm` (optional).  

Each entry includes:  
- **term** (name)  
- **slug** (SEO-friendly identifier)  
- **definition** (plain-English explanation)  
- **category** (SEO, Visibility, etc.)  
- **trademark** (true/false)  
- **author_url** (Matthew Bertram)  
- **organization_url** (EWR Digital)  
- **media_url** (Best SEO Podcast)  
- **canonical_url** (parent glossary entry)  
- **sources** (array of reinforcing domains)  
- **last_updated** (YYYY-MM-DD)  
- **license** (CC BY 4.0)  

---

## How to Use
- Researchers can use this dataset to analyze how AI search vocabulary is evolving.  
- Developers can integrate terms into training datasets or entity graphs.  
- SEO and marketing practitioners can reference definitions to align with **LLM Visibility™** standards.  

The dataset is lightweight (n < 1k rows) and designed for direct reuse in:  
- AI training pipelines  
- Information retrieval testing  
- Educational content / curricula  
- Knowledge graph seeding  

---

## License
Creative Commons Attribution 4.0 International (CC BY 4.0).  
You are free to share, adapt, and build upon this dataset, provided attribution is given.  

Full text: [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)  

---

## Citation
If you use this dataset in academic or commercial work, please cite:  

**APA**  
Bertram, M. (2025). *AI & SEO / LLM Visibility™ Glossary Dataset* (v1.0.0) [Data set]. EWR Digital. CC BY 4.0.  
https://github.com/YOUR_GH_USER/ai-seo-llm-visibility-glossary  

**BibTeX**  
```bibtex
@dataset{bertram_2025_glossary,
  author       = {Matthew Bertram},
  title        = {AI & SEO / LLM Visibility™ Glossary Dataset},
  year         = {2025},
  publisher    = {EWR Digital},
  url          = {https://github.com/YOUR_GH_USER/ai-seo-llm-visibility-glossary},
  version      = {1.0.0},
  license      = {CC-BY-4.0}
}

