# Advanced Chat Interactions Workflow

This workflow is designed to handle complex chat interactions. It processes user input and chat history, and can integrate with a weather API to provide weather information if requested by the user.

## Prerequisites

- Weather API key

## Workflow Details

- **Input Schema**:
  - `user_input`: The latest input from the user.
  - `chat_history`: An array of previous chat messages, each with a role and content.

- **Tools**:
  - `weather_api`: Integration with a weather service to fetch weather data.

- **Main Steps**:
  1. Summarize recent chat history if it exceeds five messages.
  2. Check if the user input mentions weather and fetch weather data if needed.
  3. Generate a response based on the summarized history and any weather information.

## Usage

This workflow is suitable for applications requiring advanced chat capabilities, including context management and external data integration.
