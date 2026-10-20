# Hey, I'm Kishan.

I build **full-stack products, backend systems, and search tools**. What interests me most is the work behind a reliable product: making messy data useful, figuring out why something is slow, and fixing the edge cases that show up after a demo works.

I'm an **M.S. Computer Science student at Northeastern University** in Boston, a graduate teaching assistant, and a former full-stack developer intern. My work spans web engineering, data systems, and applied NLP research.

**Seeking Winter / Summer 2027 co-ops and internships** in software engineering, backend/full-stack development, and applied AI/ML.

[Portfolio](https://kishanprajapati.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/kishan-prajapati-617a00202/) · [Google Scholar](https://scholar.google.com/citations?user=AqL9YRcAAAAJ) · [Email](mailto:prajapati.kish@northeastern.edu)

---

## Selected work

### [Sieve — research search and data infrastructure](https://kishanprajapati.vercel.app/work/sieve/)

`Python` · `FastAPI` · `PostgreSQL / pgvector` · `React` · `TypeScript` · `Docker`

**Solo project.** Built a full-stack system for searching and reviewing research literature.

- Ingested and deduplicated nearly **197,000 records** into a corpus of **182,853 papers**, with source provenance and reversible merge operations.
- Combined keyword and semantic search using PostgreSQL and HNSW. Measured **9.9 ms median end-to-end vector-search latency** on a local M1 MacBook Air.
- Reworked the source-query strategy to cut metered ingestion cost **4.6×**, collecting approximately 200,000 records in **24 minutes**.

[Technical case study](https://kishanprajapati.vercel.app/work/sieve/) · [Live demo](https://getsieve.vercel.app/)

*The full corpus runs locally; the public demo uses a 47,617-paper subset to fit free hosting.*

### [Gatekeepn't — medical-text simplification and LLM evaluation](https://github.com/Kishan-prajapati-242/Gatekeepnt)

`Python` · `PyTorch` · `Llama 3.1 8B` · `QLoRA` · `Hugging Face`

**Five-person NLP research project at Northeastern.** Studied whether fine-tuned models actually simplify unfamiliar medical text, or just learn to imitate the style of their training data.

- Trained and evaluated models on roughly **239,000 examples**, with comparisons across **28 model–dataset conditions**.
- Found that large in-domain benchmark gains did **not** necessarily translate to better out-of-domain results or better medical-entity preservation.

### [Developer portfolio — project write-ups and code](https://github.com/Kishan-prajapati-242/kishan-portfolio)

`Astro` · `TypeScript` · `CSS`

Built my portfolio with project case studies, reusable components, and checks for layout, accessibility, motion, and build quality.

[Live website](https://kishanprajapati.vercel.app/)

### [MoodLens — multi-attribute text analysis](https://huggingface.co/spaces/kishansp242/MoodLens)

`Python` · `DeBERTa-v3` · `FastAPI` · `Hugging Face`

Built an NLP demo that classifies attributes such as emotion, sentiment, sarcasm, event type, tense, and certainty from text.

---

## Technologies

| Area | Tools |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, Java, SQL, C++ |
| **Frontend & backend** | React, Node.js, Express, FastAPI, REST APIs, WebSockets |
| **Data & tooling** | PostgreSQL, MongoDB, pgvector, Docker, Git, GitHub Actions |
| **Machine learning** | PyTorch, Hugging Face Transformers, scikit-learn, ONNX Runtime |

## Research, work & teaching

- **Software developer intern, Technonite:** Worked on production applications across logistics, healthcare, and e-commerce, including a real-time vehicle-tracking dashboard.
- **Graduate teaching assistant, Northeastern:** Supported undergraduate courses in Algorithms and Data, Foundations of Data Science, and Discrete Structures.
- **NLP researcher:** Co-authored peer-reviewed work on depression detection published in Springer proceedings, and contributed to medical-text simplification research.
- **Competitive Programming Head, GDSC:** Organized 15+ contests and helped students learn algorithms and problem-solving.

---

Interested in collaborating or discussing an internship? [Get in touch](mailto:prajapati.kish@northeastern.edu).
