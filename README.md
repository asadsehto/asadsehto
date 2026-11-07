# Asad Saleem

**AI Engineer · Independent Researcher · LLM Agents & Computer Vision**

I build AI applications and do research across AI, agents and computer science. I'm pursuing a **BS in Computer Science (AI) at Sukkur IBA
University, expected August 2027**.

[LinkedIn](https://www.linkedin.com/in/asadsaleemsahto/) · [Kaggle](https://www.kaggle.com/asadsahto) · [Portfolio](https://asadsahto.netlify.app/) · [Email](mailto:asadsaleemsahto@gmail.com)

### Research

**[Self-Improving Harnesses Below the Capability Floor](https://github.com/asadsehto/continual-harness-small-models)** (2026)

Can a small model running on a laptop rewrite its own prompt, memory and tools and get better?
I re-implemented Continual Harness (Karten et al., 2026) for local Ollama models and tested it on
`qwen3.5:0.8b` and `gemma4:e2b` across 20 automatically checked computer tasks.

- Self-editing as-is made both models **worse** than a fixed harness (32% → 15% and 92% → 77%).
- Five added safeguards together (a larger refiner, a regression gate, retrieval memory, verified
  skills, structured errors) brought the small model back to baseline, with a suggestive gain on
  held-out tasks (27% → 60%).
- Reported with paired exact tests, Holm correction, per-seed results and a released dataset of
  1,256 runs; one command rebuilds every table.

### Current focus

- **LecAssist** — my agentic academic-assistance thesis (2026–2027), exploring lecture transcription,
  grounded question answering, and evaluation of multi-step agent workflows. The public
  [thesis workspace](https://github.com/asadsehto/fyp) includes an Aura desktop recording assistant
  and portal-automation work.

### Experience

| Role | Organization | Dates |
| --- | --- | --- |
| AI Engineer | Miami TV | December 2025–present |
| Junior AI Engineer | Memo Apps | September–November 2025 |
| Python Developer | Easy.co | June–August 2025 |

At Miami TV, my work includes agent workflows for research and content generation, a retrieval-based
assistant, and streaming analytics. My previous roles covered educational software, workflow
automation, and data-extraction pipelines.

### Selected work

| Project | Focus |
| --- | --- |
| [Continual Harness on small models](https://github.com/asadsehto/continual-harness-small-models) | Research code for the paper above: agent loop, sandbox, self-editing refiner, five safeguards, 20 tasks with checkers, and released data. |
| [ProfDesk](https://github.com/asadsehto/profdesk) | Self-hosted assistant that puts Claude, ChatGPT and a private local model in one chat, usable from a phone. Built for teachers. |
| [Tribunal](https://tribunal.app) | Multi-agent reasoning platform exploring structured debate, counterarguments, and synthesis with Python, TypeScript, Node.js, and LLM APIs. |
| [Quantum-RAG](https://github.com/asadsehto/Quantum-RAG) | Python semantic-retrieval prototype with chunking, embeddings, vector search, and separate quantum-inspired experiments. |
| [Rizzume](https://github.com/asadsehto/rizzume) | Resume builder connecting a React interface to Flask and LaTeX PDF generation. |
| [CareToShare](https://github.com/asadsehto/CareToShare) | Student study-material sharing with React, Express, MongoDB, Google OAuth, and Google Drive integration. |

Additional work includes [ALIF-AI](https://github.com/asadsehto/ALIF-AI) and a [semantic book recommender](https://github.com/asadsehto/semantic-book-recommender).

### Tools I work with

**ML & AI:** PyTorch · TensorFlow · scikit-learn · Transformers · Ollama · NumPy · Pandas  
**Research:** experiment design · paired significance testing · ablations · LaTeX  
**Software & deployment:** Python · FastAPI · Flask · React · Node.js · Docker · Linux · GCP · MongoDB · Redis

For AI/ML engineering opportunities, research collaboration and project enquiries, contact me by
[email](mailto:asadsaleemsahto@gmail.com) or [LinkedIn](https://www.linkedin.com/in/asadsaleemsahto/).
