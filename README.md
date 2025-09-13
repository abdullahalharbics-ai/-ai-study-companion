# -ai-study-companion
# AI Study Companion (Portfolio Project 1)

## Purpose
A small tool that ingests my course PDFs/slides and answers questions via Retrieval-Augmented Generation (RAG). It helps me study faster for SEU/KKU + the AI diploma and serves as a resume-ready project.

## Scope
**In:** PDF ingestion, text chunking, embeddings, vector store, simple Q&A; basic UI.  
**Out (for now):** multi-user accounts, databases beyond local, speech features, complex design.

## Objectives & Success
- **MVP (Oct–Nov 2025):** Upload PDF → ask question → get grounded answer.  
- **Accuracy:** ≥80% correct on my own slides/questions.  
- **DX:** Clear README + setup steps so another student can run it.

## Milestones & Timeline
- **Sep 13–15, 2025:** Kickoff complete (repo, README, plan). ← **THIS SUBMISSION**
- **Sep–Oct 2025 (Phase 0):** Python foundations  to prep.
- **Oct–Nov 2025:** Build MVP in a notebook → then move to app.
- **Dec 2025–Feb 2026:** Add UI (Streamlit), summaries/flashcards, polish docs.
- **Later:** Deploy demo; write 1 technical post summarizing lessons.

## Tech Stack (initial)
- **Python 3.11**, **LangChain** or **LlamaIndex**
- **Embeddings:** `sentence-transformers/all-MiniLM-L6-v2` (local) or API
- **Vector store:** **Chroma**
- **PDF parsing:** `pypdf`
- **UI:** **Streamlit** (simple), can be swapped to SP stack later

## Repo Layout (planned)
