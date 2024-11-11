# Generate User Persona Workflow

This workflow creates detailed user personas based on user data and reading history.

## Workflow Details

- **Input Schema**:
  - `user_ppid`: User's unique identifier
  - `articles_read`: Array of read articles
  Required fields: Both fields are mandatory

- **Tools**:
  - `get_user_from_ppid`: User data retrieval system
  - `list_user_docs`: User document listing system
  - `create_user_doc`: User document creation system

- **Main Steps**:
  1. User Data Retrieval
     - Fetch user information by PPID
     - Sort by recent activity
  2. Document Analysis
     - Retrieve existing persona documents
     - Extract current persona data
  3. Persona Generation
     - Analyze demographics
     - Evaluate psychographics
     - Map content interests
     - Assess sports preferences
  4. Document Creation
     - Generate embedding instruction
     - Create new persona document
     - Store with proper formatting

## Usage

Perfect for platforms requiring sophisticated user profiling and content personalization.
