# Hook Generator Trending Reels Workflow

This workflow generates engaging hooks for trending social media reels based on a given topic.

## Prerequisites

- RapidAPI key for Instagram Scraper API
- Agent system for hook template storage

## Workflow Details

- **Input Schema**:
  - `topic`: The topic to search for trending reels

- **Tools**:
  - `api_tool_call`: Instagram Scraper API integration for fetching trending reels
  - `get_hooks_doc`: Retrieves hook templates from agent documents

- **Main Steps**:
  1. Data Collection
     - Fetch trending reels by keyword using Instagram API
     - Process media metadata and statistics
  2. Content Analysis
     - Extract captions and media information
     - Calculate virality and engagement scores
  3. Description Generation
     - Process reel content in parallel (4 threads)
     - Generate JSON responses with metrics
  4. Hook Creation
     - Retrieve hook templates from agent
     - Generate 3 hooks per reel using templates
     - Ensure hooks are topic-focused and engaging
  5. Optimization
     - Parallel processing for efficiency
     - Format and structure final output

## Usage

Ideal for:

- Social media content creators
- Marketing automation systems
- Engagement optimization tools

## Performance Notes

- Uses parallel processing (4 threads) for content analysis
- Implements efficient JSON response handling
