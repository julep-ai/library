# Managing Persistent Sessions Workflow

This workflow handles user session management and context preservation.

## Workflow Details

- **Input Schema**:
  - `user_input`: Current user input
  - `session_context`: Existing session context object

- **Main Steps**:
  1. Context Processing
     - Evaluate current session context
     - Process new user input
  2. Response Generation
     - Generate contextual response
  3. Context Update
     - Update session with new interaction
     - Preserve response in context

## Usage

Ideal for applications requiring stateful conversation management.
