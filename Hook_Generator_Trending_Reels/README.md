# Hook Generator Trending Reels Workflow

This workflow generates engaging hooks for trending social media reels based on a given topic.

## Prerequisites

- RapidAPI key for Instagram Scraper API

## Workflow Details

- **Input Schema**:
  - `topic`: The topic to search for trending reels

- **Tools**:
  - `api_tool_call`: Calls an external API to fetch trending reels data.
  - `get_hooks_doc`: Retrieves hook templates for generating hooks.

- **Main Steps**:
  1. Fetch trending reels data using an external API.
  2. Generate descriptions and scores for each reel.
  3. Retrieve hook templates.
  4. Generate engaging hooks for each reel using the templates.

## Usage

Ideal for social media managers and content creators needing automated, engaging hook generation for trending content.
