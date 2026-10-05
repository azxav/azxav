# Azizbek Xasanov

**AI & ML Engineer · Tashkent, Uzbekistan**

I build ML systems and measure them honestly: computer vision, recommender systems, tabular models,
and retrieval-augmented LLM tools. I'm studying AI & Robotics at New Uzbekistan University and have
worked on RAG, adaptive testing, and generated explainer videos in two AI & ML developer roles. I care about
validation, reproducibility, and saying clearly what a number does and doesn't prove.

## Featured projects

| Project | What it is | Result |
| --- | --- | --- |
| [2Brain](https://2brainai.tech) | Corporate AI assistant with a managed memory layer, permission-aware retrieval, and agents that cite sources (or name the gap) | Live product at 2brainai.tech; memory layer uses gbrain (MIT) |
| [agent-platform](https://github.com/azxav/agent-platform) | Multi-agent FastAPI service: pack registry, per-run cost caps, SSE, mock LLM, golden evals | 908 tests; golden evals 10/10 under mock |
| [bank-doc-rag](https://github.com/azxav/bank-doc-rag) | Multilingual bank-document RAG: LangGraph + Qdrant citations, offline demo | Offline demo works; full eval table blocked by OpenRouter credits |
| [uzbek-voice-agent](https://github.com/azxav/uzbek-voice-agent) | Uzbek speech demo: FastAPI upload + optional LiveKit worker with NavAI whisper-small-uzbek | WER 14.29% / CER 7.00% on 7 unique FLEURS uz_uz test-prefix utterances (not NavAI’s full-set figure) |
| [kaggle-S6E3](https://github.com/azxav/kaggle-S6E3) | Customer churn prediction (Kaggle Playground S6E3): feature-family sweeps, GBDTs, tabular deep nets, DVAE features, stacking | Rank 57 of 4,142 (top 1.4%), score 0.91824 |
| [kgmon](https://github.com/azxav/kgmon) | MCP server + CLIs that turn a Kaggle competition into a local, validation-first workspace with leakage checks, packaging, and guarded submission | 19 MCP tools; secret redaction and confirm-before-submit |
| [orbit_warsv2](https://github.com/azxav/orbit_warsv2) | Set-transformer behaviour-cloning agent for the Orbit Wars Kaggle game, trained on winner replays (successor to my [JAX PPO agent](https://github.com/azxav/orbit_wars)) | 18M-param export won 8/8 local games vs a nearest-planet baseline (small sample, not a leaderboard rank) |
| [traffic-vision](https://github.com/azxav/traffic-vision) | Fixed-camera traffic event detection (congestion, failure to yield, red-light running) with YOLO11s, ByteTrack, and junction rules | Score A 0.5084 (up from 0.4684 after a signal-rule change); precision 0.73 / 0.85 / 1.00 at temporal IoU 0.5 on 118 reviewed intervals |
| [recsys_kuirand](https://github.com/azxav/recsys_kuirand) | Two-stage short-video recommender on KuaiRand: ALS / ItemKNN / EASE retrieval + monotone CatBoost ranker, FastAPI serving skeleton | On the unbiased random-policy log, calibrated ranker AUC 0.644 vs 0.572 for popularity, log loss 0.497 vs 0.512 |

agent-platform, bank-doc-rag, uzbek-voice-agent, traffic-vision, recsys_kuirand, kaggle-S6E3, kgmon, and orbit_warsv2 are personal projects.
Each README states its evaluation setup and limitations.

## Skills

- **ML & DL:** Python, PyTorch, Keras, scikit-learn, XGBoost, LightGBM, CatBoost, JAX
- **Applied areas:** computer vision (Ultralytics YOLO, ByteTrack), recommender systems, tabular ML, RAG and LLM agents (MCP)
- **MLOps & tools:** FastAPI, Docker, MLflow, MongoDB, Google Cloud, AWS, Git

## Experience

- **SATashkent** · AI & ML Developer · 2025. Worked on an adaptive testing system that picks the question sets that improve each student's skills most efficiently, and on a system that generates animated explanation videos from SAT questions.
- **Mutolaa** · AI & ML Developer · 2024. Developed a retrieval-augmented generation (RAG) system; used fairseq to automate data preparation for TTS model training.

## Education

**New Uzbekistan University**, Bachelor's in Artificial Intelligence & Robotics, 2024–2028

## Honours

URBAN.TECH Hackathon, 1st place (Industry Tech) · CBU Coding Challenge, 3rd place ·
Ideathon at the 4th World Conference on Creative Economy, honourable mention

## Contact

- Email: [azxav000@gmail.com](mailto:azxav000@gmail.com)
- LinkedIn: [azizbek-xasanov](https://www.linkedin.com/in/azizbek-xasanov/)
- Languages: English, Russian
