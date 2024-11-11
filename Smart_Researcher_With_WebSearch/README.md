# Smart Researcher With WebSearch Workflow

This workflow performs intelligent research on trending topics using web search and keyword extraction.

## Prerequisites

- Brave Search API key

## Workflow Details

- **Input Schema**:
  - `topics`: Array of topics to research

- **Tools**:
  - `brave_search`: Integration with Brave search engine

- **Main Steps**:
  1. Topic Research
     - Search latest news for each topic
     - Use parallel processing (2 threads)
  2. Keyword Extraction
     - Analyze news content
     - Generate Wikipedia-ready keywords
  3. Result Formatting
     - Format keywords as comma-separated list
     - Remove extraneous text

## Usage

Perfect for:

- Research automation systems
- Content discovery tools
- Trending topic analysis
