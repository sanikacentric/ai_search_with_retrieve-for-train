TRADITIONAL LLM SEARCH

User Query
    ↓
Large LLM
    ↓
Think / Reason
    ↓
Generate Q1 → Q2 → Q3 → Q4...
    ↓
Retrieve
    ↓
Results


RETRIEVE-FOR-TRAIN

          OFFLINE
Large LLM + RL
      ↓
Learn good fan-out
      ↓
Generate training examples
      ↓
Train small diffusion model
      ↓
────────────────────────────
          ONLINE
User Query
      ↓
Small Diffusion Retriever
      ↓
Multiple Retrieval Embeddings
      ↓
Vector Search
      ↓
Results
