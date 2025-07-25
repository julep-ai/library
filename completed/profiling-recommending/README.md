# Profiling and Recommending Workflow

This example contains two agents and two tasks:

- **ProfilerAgent**: It is used to create/update the profile of the user
- **RecommenderAgent**: It is used to recommend the title of the article to the user

- **GenerateUpdatePersonaTask**: It is used to generate/update the profile of the user
- **RecommendNewsArticlesTask**: It is used to recommend the title of the article to the user

## Workflow Details

### Profiler Workflow

- **Input Schema**:
  - `user_ppid`: User's unique identifier
  - `articles_read`: Array of read articles
  Required fields: Both fields are mandatory

- **Tools**:
  - `get_user_from_ppid`: User data retrieval system
  - `list_user_docs`: User document listing system
  - `create_user_doc`: User document creation system

- **Main Steps**:
  1. User Data Retrieval
     - Fetch user information by PPID
     - Sort by recent activity
  2. Document Analysis
     - Retrieve existing persona documents
     - Extract current persona data
  3. Persona Generation
     - Analyze demographics
     - Evaluate psychographics
     - Map content interests
     - Assess sports preferences
  4. Document Creation
     - Generate embedding instruction
     - Create new persona document
     - Store with proper formatting

#### Usage

Perfect for platforms requiring sophisticated user profiling and content personalization.

### Recommender Workflow

- **Input Schema**:
  - `user_ppid`: User's unique identifier
  - `mmr_strength`: MMR (Maximal Marginal Relevance) strength for content diversity
  - `agent_id`: Agent identifier for document search
  Required fields: All fields are mandatory

- **Tools**:
  - `get_user_from_ppid`: Retrieves user information from PPID
  - `get_user_docs`: Fetches user documents and persona
  - `search_agent_docs`: Searches and ranks agent documents using embedding similarity

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

#### Usage

This workflow is ideal for personalized news recommendation systems requiring:

- Sport content diversification
- Persona-based content ranking
- Automated newsletter generation
