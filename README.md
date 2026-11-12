# Istiyak Hossain Ishan

**Applied AI Engineer & Multilingual LLM Researcher**  
Undergraduate Thesis Researcher & B.Sc. in Data Science (Inaugural Batch) @ United International University (UIU) · Former Research Engineer Intern @ AIMS Lab (IRIIC, UIU)

I engineer production-oriented retrieval-augmented generation (RAG) systems, asynchronous LLM evaluation harnesses, and parameter-efficient adaptation pipelines. My research investigates **how continual domain adaptation (CPT/SFT, LoRA/QLoRA) and quantization affect knowledge conflict, catastrophic forgetting, and safety alignment across asymmetric, low-resource language pairs (English, Bengali, and Romanized Banglish)**—with a focus on deploying reliable, pocket-efficient LLMs under real-world hardware constraints.

### Research & Engineering Focus

- **Multilingual LLM Robustness & Safety:** Investigating knowledge conflicts between parametric memory and injected domain corpora (`ConflictQA`/`CLEAR`), catastrophic forgetting of general reasoning, and register/cross-script safety alignment failures across English, Bangla, and Banglish.
- **Pocket-Efficient Language Models:** Parameter-efficient fine-tuning (`LoRA`, `QLoRA`, `PEFT`), 4-bit/8-bit quantization, ONNX runtime optimization (`MiniLM-L6-v2` 384-d embeddings), and preserving factual consistency on consumer-grade hardware.
- **Production RAG & Evaluation Systems:** Hybrid retrieval (dense vector search + sparse lexical matching), asynchronous `LLM-as-judge` grounding & hallucination pipelines, and migrating multi-service cloud RAG stacks (`FastAPI`, `Celery`, `Qdrant`, `PostgreSQL`, `Redis`, `Next.js`) into installable local-first desktop architectures supporting interchangeable local and cloud models.

### Featured Systems & Repositories

| Repository | Domain | Key Architecture & Benchmarks |
| :--- | :--- | :--- |
| [**Quantiva**](https://github.com/Istiyak-Ishan/Quantiva) | Production & Local-First RAG | Full-stack document intelligence workspace with cited Q&A, SSE streaming, and async ingestion (`FastAPI`, `Celery`, `SQLAlchemy`, `Qdrant`, `PostgreSQL`, `Redis`, `S3`, `Next.js`, `TypeScript`, `Zustand`), actively evolving into a local-first desktop RAG application supporting interchangeable local and API models |
| [**LLM-Evaluation-Harness**](https://github.com/Istiyak-Ishan/LLM-Evaluation-Harness) | Grounding & Hallucination Scoring | Asynchronous `asyncio` + `Pydantic` evaluation pipeline measuring answer faithfulness, semantic similarity, and hallucination rates across QA benchmarks using Gemini as an automated judge |
| [**domain-adapted-classifier**](https://github.com/Istiyak-Ishan/domain-adapted-classifier) | PEFT & Representation Drift | `DistilBERT` + `LoRA` domain adaptation pipeline evaluating trainable parameter budgets, representation drift, and accuracy/latency trade-offs across zero-shot, few-shot, and fine-tuned regimes with attention interpretability |
| [**med-rec-mlsd**](https://github.com/Istiyak-Ishan/med-rec-mlsd) | MLOps & Semantic Retrieval | Reproducible ML System Design (`DVC` + `FastAPI`) replacing sparse lexical search with 384-d `MiniLM` ONNX semantic embeddings (~22 MB model) across a 2,544-item Bangladeshi pharmaceutical catalog (`0.9369` mean similarity, `0.1742` catalog coverage) |
| [**ajaia-docs**](https://github.com/Istiyak-Ishan/ajaia-docs) | Full-Stack Web Engineering | Collaborative rich-text workspace (`Next.js 14 App Router`, `TypeScript`, `Tiptap`, `Prisma`, `PostgreSQL`) featuring `.txt`/`.md`/`.docx` import parsing, role-based access control (`OWNER`/`EDIT`/`VIEW`), and `Vitest` test coverage |
| [**Semantic-Search-Engine**](https://github.com/Istiyak-Ishan/Semantic-Search-Engine) | Information Retrieval | Dual-model retrieval benchmark over an ArXiv scientific corpus comparing sparse lexical matching (`TF-IDF`) against dense distributed vector spaces (`GloVe`) on high-divergence queries |
| [**transformer-from-scratch**](https://github.com/Istiyak-Ishan/transformer-from-scratch) | Deep Learning Foundations | Decoder-only Mini-GPT implemented from first principles in `PyTorch` and `NumPy` with multi-head causal self-attention and mathematical derivations |
| [**UniqToken**](https://github.com/Istiyak-Ishan/UniqToken) | Multilingual Tokenization | High-precision byte-fallback Unigram & `SuperBPE` tokenizer with `Rust` (`PyO3`) native acceleration, dual-offset span tracking, and Unicode grapheme cluster protection for Indic/Bangla scripts |
| [**steam-market-intelligence**](https://github.com/Istiyak-Ishan/steam-market-intelligence) | Applied ML & Market Modeling | Empirical market intelligence platform analyzing 57,506 paid Steam titles using `Ridge` regression, `Random Forest`, and `K-Means` clustering to guide indie pricing and positioning |

### Technical Stack

- **Deep Learning & NLP:** `PyTorch`, `Hugging Face (transformers, peft, datasets, accelerate)`, `LoRA / QLoRA`, `Sentence-Transformers`, `ONNX Runtime`, `Scikit-Learn`, `XGBoost`, `Optuna`, `SHAP`
- **Backend, RAG & MLOps:** `Python 3.11`, `FastAPI`, `Celery`, `SQLAlchemy (Async)`, `Pydantic`, `Qdrant`, `PostgreSQL`, `Redis`, `SQLite`, `DVC`, `Docker`, `GitHub Actions CI`
- **Frontend & Systems:** `TypeScript`, `Next.js (App Router)`, `React`, `Tailwind CSS`, `Zustand`, `Prisma`, `C/C++`, `Bash / Linux CLI (WSL2 & Pop!_OS)`, `LaTeX`

### Connect

- **Email:** [istiyakishan7@gmail.com](mailto:istiyakishan7@gmail.com)
- **GitHub:** [github.com/Istiyak-Ishan](https://github.com/Istiyak-Ishan)
- **Location:** Dhaka / Chittagong, Bangladesh (Open to remote AI Engineering roles & funded graduate research collaborations in the US, Canada, and Germany)