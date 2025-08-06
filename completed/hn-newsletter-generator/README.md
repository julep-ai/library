# HN Newsletter Generator

A powerful Julep template that creates personalized Hacker News newsletters by fetching top stories, analyzing their relevance to user interests, and generating AI-powered summaries.

## Features

- **Fetch Top Stories**: Retrieves the latest top stories from Hacker News API
- **Smart Filtering**: Filters stories based on minimum score threshold
- **Web Scraping**: Extracts full article content using Spider integration
- **Comment Analysis**: Fetches top comments for additional context
- **AI Personalization**: Scores stories based on user's technology interests
- **Auto-Summarization**: Generates concise 100-word summaries for each story
- **Parallel Processing**: Optimized for performance with parallel API calls

## Input Parameters

- `min_score` (integer, default: 50): Minimum HN score threshold for stories
- `num_stories` (integer, default: 10): Number of stories to include in newsletter
- `user_preferences` (array): User's technology interests (e.g., ["AI/ML", "Python", "Startups"])

## Output Format

The task returns an array of personalized stories, each containing:
- `title`: Story title
- `url`: Original article URL
- `hn_url`: Hacker News discussion URL
- `comments_count`: Number of comments
- `summary`: AI-generated summary

## Requirements

- Spider API key for web scraping (set as `spider_api_key` in the Spider integration setup)

## Usage Example

```python
execution = client.executions.create(
    task_id=task.id,
    input={
        "min_score": 100,
        "num_stories": 5,
        "user_preferences": ["AI/ML", "Python", "DevOps", "Cloud Computing"]
    }
)
```

## How It Works

1. Fetches top 50 story IDs from Hacker News
2. Retrieves full details for each story in parallel
3. Filters stories by minimum score and limits to requested number
4. Scrapes full article content using Spider
5. Fetches top 3 comments per story for context
6. Uses AI to score relevance (0-100) based on user preferences
7. Filters stories with relevance >= 60
8. Generates concise summaries for personalized stories
9. Returns formatted newsletter content

## Customization Ideas

- Add email integration to send newsletters automatically
- Set up scheduling for daily/weekly newsletters
- Integrate with RSS feeds or other news sources
- Add sentiment analysis for comments
- Export to different formats (HTML, PDF, Markdown)