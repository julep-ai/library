# Documentation Customer Support

An intelligent AI support assistant built with the Julep platform to help developers understand and use Julep effectively. This project demonstrates best practices for building AI applications with Julep, including web crawling, document indexing, and conversational AI capabilities.

## Overview

The Documentation Customer Support workflow is designed to help users navigate through documentation, provide answers to FAQs, and assist with common support queries. This workflow improves user experience by providing intelligent, context-aware responses based on documentation content.

## Features

- **Intelligent Documentation Crawling**: Automatically crawls and indexes Julep documentation using Spider integration
- **RAG-powered Conversations**: Uses Retrieval-Augmented Generation for accurate, context-aware responses
- **Enhanced Document Processing**: Extracts and categorizes code examples, concepts, and Q&As from documentation
- **Parallel Processing**: Efficiently processes multiple documentation pages simultaneously
- **Contextual Search**: Creates searchable content optimized for retrieval with relevant questions and answers
- **Code Example Extraction**: Identifies and preserves code examples with proper context and explanations

## How It Works

1. **Web Crawling**: Uses Spider integration to crawl Julep documentation pages
2. **Content Analysis**: Analyzes each page to extract primary concepts, content type, and key topics
3. **Chunking**: Splits content into ~1500 word chunks with overlap for better context preservation
4. **Enhancement**: Generates Q&As and searchable content for each chunk
5. **Document Storage**: Stores enhanced content in Julep's document store with metadata for efficient retrieval

## Agent Configuration

The assistant is configured with:
- **Model**: Claude Sonnet 4 for high-quality responses
- **Capabilities**: Workflow assistance, concept explanation, code examples, API guidance, and best practices
- **Instructions**: Comprehensive guidelines for helping developers with Julep platform

## Task Structure

The task includes three main workflows:
- **Main Workflow**: Entry point that initiates web crawling
- **Process Single Page**: Handles individual page processing and chunking
- **Index Page**: Performs content analysis, code extraction, and document creation

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `spider_api_key` | Spider API key for web crawling | Yes |

## Use Cases

- Help developers write, debug, and optimize Julep workflows
- Explain Julep concepts like agents, tasks, sessions, and tools
- Provide working code examples in Python, YAML, or JavaScript
- Guide users through Julep's API usage
- Share proven patterns and architectural recommendations
- Answer questions about Julep documentation and features