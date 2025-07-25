# Personalized Research Paper Recommendation Assistant

This workflow is designed to recommend research papers tailored to individual user personas by leveraging various search and integration tools.

## Prerequisites

- Integration with Brave Search for topic-based news retrieval
- Integration with Arxiv for research paper search
- Llama Parse for scraping and parsing document contents
- User and document management systems

## Workflow Details

- **Input Schema**:
  - `topics`: An array of topics to search for
  - `user_id`: The user's unique identifier

- **Tools**:
  - `brave_search`: Searches for the latest news snippets based on topics
  - `arxiv_search`: Searches for research papers based on extracted keywords
  - `llama_parse_scrape`: Parses and scrapes document contents from URLs
  - `get_user_from_id`: Retrieves user information using ID
  - `get_user_docs`: Fetches user documents and persona
  - `create_user_doc`: Creates a new document for the user

- **Main Steps**:
  1. **Topic Search**:
     - Use Brave Search to find the latest news snippets for each topic.
  2. **Keyword Extraction**:
     - Extract keywords from news snippets to identify relevant research areas.
  3. **Research Paper Search**:
     - Use Arxiv Search to find papers based on the top keywords.
  4. **User Persona Retrieval**:
     - Retrieve user information and persona using PPID.
  5. **Paper Selection**:
     - Select the top 5 research papers that align with the user's persona.
  6. **Content Scraping**:
     - Use Llama Parse to scrape and parse the contents of selected papers.
  7. **Document Creation**:
     - Create a new document for the user with the scraped paper contents.

## Usage

This workflow is ideal for systems that require personalized research paper recommendations based on user interests and professional needs. It ensures that the recommendations are relevant and beneficial for the user's ongoing research and professional development.
