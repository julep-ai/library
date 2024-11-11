# Integrating External Tools and APIs Workflow

This workflow creates comprehensive analysis reports using multiple external data sources.

## Prerequisites

- Brave Search API key
- OpenWeatherMap API key
- Wikipedia API access

## Workflow Details

- **Input Schema**:
  - `topic`: Main analysis topic
  - `location`: Location for weather analysis

- **Tools**:
  - `brave_search`: Web search integration
  - `weather`: Weather data service
  - `wikipedia`: Wikipedia information retrieval

- **Main Steps**:
  1. Data Collection
     - Execute web search for latest developments
     - Fetch location weather data
     - Retrieve Wikipedia topic information
  2. Report Generation
     - Create overview from Wikipedia data
     - Include latest developments
     - Add weather impact analysis
     - Synthesize conclusions

## Usage

Suitable for applications requiring comprehensive data analysis from multiple sources.
