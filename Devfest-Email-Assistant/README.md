# Devfest Email Assistant Workflow

This workflow assists in managing email communications for Devfest events by generating responses based on user inquiries.

## Prerequisites

- Mailgun account with API key

## Workflow Details

- **Input Schema**:
  - `from`: Sender's email address.
  - `to`: Recipient's email address.
  - `subject`: Subject of the email.
  - `body`: Body content of the email.

- **Tools**:
  - `send_email`: Integration with an email service to send responses.
  - `search_docs`: System tool to search documentation for relevant information.

- **Main Steps**:
  1. Generate a query to search documentation based on the email content.
  2. Search for relevant documentation snippets.
  3. Craft a response email using the found snippets.
  4. Send the crafted email response.

## Usage

This workflow is useful for automating email responses, especially in event management contexts.
