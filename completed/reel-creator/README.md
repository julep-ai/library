# Reel Creator Workflow

This workflow generates viral social media reels by analyzing trending content and creating engaging video content.

## Prerequisites

- RapidAPI key for Instagram Scraper API
- Replicate API key for image and audio generation
- Jina API key for web search

## Workflow Details

- **Input Schema**:
  - `topic`: The topic to generate reel content for

- **Tools**:
  - `api_tool_call`: Fetches trending reels from Instagram
  - `get_page`: Retrieves webpage content
  - `get_replicate_model`: Generates images and audio
  - `get_replicate_url`: Retrieves replicate URLs
  - `get_hooks_doc`: Accesses hook templates
  - `create_reel`: Creates video content
  - `get_reel_url`: Retrieves video URLs

- **Main Steps**:
  1. Analyze trending Instagram reels
  2. Create engaging video script and scenes
  3. Generate images and audio for each scene
  4. Combine assets into final video reel
  5. Create viral social media copy

## Usage

Ideal for content creators and social media managers who want to:

- Generate viral social media reels automatically
- Create engaging video content based on trends
- Produce complete reel packages with captions and assets

The workflow handles the entire reel creation pipeline from trend analysis to final video production.
