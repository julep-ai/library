# News Recommender Workflow

This workflow recommends personalized news articles to users based on their persona and reading history.

## Prerequisites

- User system integration
- Document management system

## Workflow Details

- **Input Schema**:
  - `user_ppid`: The user's unique identifier
  - `mmr_strength`: MMR (Maximal Marginal Relevance) strength for content diversity
  - `agent_id`: Agent identifier for document search

- **Tools**:
  - `get_user_from_ppid`: Retrieves user information from PPID
  - `get_user_docs`: Fetches user documents and persona
  - `search_agent_docs`: Searches and ranks agent documents using embedding similarity

- **Main Steps**:
  1. User Data Retrieval
     - Fetch latest user information using PPID
     - Retrieve most recent user documents
  2. Persona Analysis
     - Extract user embeddings and persona
     - Use embeddings for content similarity ranking
  3. Content Selection
     - Search and rank documents using MMR
     - Select top 50 articles for consideration
  4. Article Diversification
     - Rank articles based on user persona
     - Select top 5 articles with sport diversity
  5. Newsletter Generation
     - Create personalized newsletter title
     - Format final article selection

## Usage

This workflow is ideal for personalized news recommendation systems requiring:

- Sport content diversification
- Persona-based content ranking
- Automated newsletter generation
