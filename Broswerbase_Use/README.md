# Browserbase Use Workflow

This workflow enables headless browser automation for web interactions and tasks.

## Prerequisites

- Browserbase API key
- Browserbase Project ID

## Workflow Details

- **Input Schema**:
  - `goal`: The objective or task to be performed
  - `agent_id`: Identifier for the agent executing the task
  Required fields: Both fields are mandatory

- **Tools**:
  - `create_browserbase_session`: Creates a new browser session
  - `get_cdp_url`: Gets Chrome DevTools Protocol URL
  - `get_session_view_urls`: Retrieves session viewing URLs
  - `perform_browser_action`: Executes browser interactions with configurable viewport (1024x768)
  - `create_julep_session`: Creates task management session
  - `session_chat`: Handles session communication

- **Main Steps**:
  1. Initialize Julep session for task management
  2. Create Browserbase session
  3. Set up connection URLs and viewing access
  4. Navigate to initial safe page (Google)
  5. Execute browser interactions based on goal
  6. Process and evaluate results
  7. Recursively continue until goal is achieved

- **Browser Capabilities**:
  - Navigation to URLs
  - Page interaction (clicking, typing)
  - Screenshot capture
  - Single-tab operation
  - Viewport size: 1024x768

## Usage

Ideal for automated web interactions requiring headless browser capabilities, such as:

- Web automation tasks
- Content extraction
- Site interaction testing
- Automated web navigation


## Technical Notes

- Uses Chrome DevTools Protocol for browser control
- Implements recursive workflow for continuous task execution
- Provides live session viewing URLs for monitoring
- Maintains session context throughout execution
