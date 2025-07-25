# Trip Planner Workflow

This workflow generates detailed travel itineraries that incorporate weather conditions and tourist attractions for multiple locations.

## Prerequisites

- OpenWeatherMap API key
- Brave Search API key

## Workflow Details

- **Input Schema**:
  - `locations`: Array of location strings to generate plans for

- **Tools**:
  - `wikipedia`: Integration for Wikipedia information
  - `weather`: OpenWeatherMap API integration for current conditions
  - `internet_search`: Brave Search API for finding attractions

- **Main Steps**:
  1. Weather Data Collection
     - Fetch current weather for each location
  2. Attraction Research
     - Search for tourist attractions in each location
  3. Data Integration
     - Combine location, weather, and attraction data
  4. Itinerary Generation
     - Process locations in parallel (3 threads)
     - Generate detailed travel plans considering weather
     - Create personalized activity recommendations
  5. Plan Compilation
     - Format and combine all location plans
     - Present organized final itinerary

## Usage

Ideal for:

- Travel planning applications
- Tourism services
- Personal trip organization

## Performance Notes

- Uses parallel processing (3 threads) for itinerary generation
- Efficient data integration through zip operations
- Structured output formatting for readability
