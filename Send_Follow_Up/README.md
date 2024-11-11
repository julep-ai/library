# Send Follow-Up Workflow

This workflow manages automated follow-up communications.

## Workflow Details

- **Input Schema**:
  - `event_id`: Event identifier
  - `participants`: Array of participant emails
  - `follow_up_message`: Message content

- **Main Steps**:
  1. Message Processing
     - Prepare follow-up message
     - Confirm message delivery
  2. Status Return
     - Provide delivery status

## Usage

Ideal for event management systems requiring automated follow-up functionality.
