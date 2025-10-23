# Take-Home Interview Assignment: Financial Document Q&A API

## Overview

Build a REST API that enables users to ask questions about a provided financial document (PDF) with conversational capabilities and arithmetic reasoning.

**Time Allocation:** We don't expect candidates to spend more than 4hrs on this task

## The Challenge

### Required Features

1. **Document Processing**

   - Ingest and process the provided financial document (PDF format)
   - Extract and structure relevant information for querying

2. **REST API Endpoint**

   - Create an endpoint that accepts natural language questions about the document
   - Return accurate, contextually relevant answers (fact retrieval)

3. **Multi-Turn Conversations**

   - Maintain conversation context across multiple API calls
   - Handle follow-up questions that reference previous exchanges

4. **Arithmetic Capabilities**
   - Perform simple calculations based on document data (e.g., "What was the percentage change in total sales from 2023 to 2024?" <em>Requires: Finding sales for both years and calculating the percentage change</em>)

### Bonus Features (Optional)

- Support for more complex, multi-step arithmetic operations
(e.g., "If you combine the sales from Zone North America and Zone Europe, what percentage of total Group sales do these two zones represent in 2024?" <em>Requires: Finding NA sales, EUR sales, total sales, adding the two zones, then calculating percentage</em>)
- Frontend chat interface for interacting with the API
- Method for evaluating system performance and accuracy
- Additional enhancements you think would improve the user experience

## Deliverables

### 1. Working Code

- REST API implementation
- Any necessary configuration files
- Basic setup/installation instructions
- **Note:** Database usage is completely optional; in-memory storage is acceptable

### 2. Documentation (WRITEUP.md)

Include the following sections:

- **Methodology:** Your approach and architectural decisions
- **Performance Evaluation:** How you tested accuracy and what the results were
- **Improvements:** What you would enhance in this POC given more time
- **Production Readiness:** What would need to be addressed to deploy this to production
- **AI Disclosure:** Any AI tools used during development (e.g., Claude, ChatGPT, Copilot)

### 3. Setup Instructions

- Clear steps to run your solution locally
- List of dependencies and how to install them
- Any environment variables or configuration needed

## Constraints & Guidelines

- **No Agentic Coding Tools:** Do not use AI-powered coding assistants like Claude Code, Cursor, GitHub Copilot Agent mode, or similar agentic tools. Standard IDE features and documentation are fine.
- **Technology Stack:** Use whatever technologies you're most comfortable with, but in regards to programming languages please use Python and/or Typescript
- **Scope:** We understand this is a vauge brief, please get as far as you can without spending excessive amounts of time on the task

## Evaluation Criteria

We'll assess your submission based on:

- Correctness and functionality of core features
- Ability to use Ai technologies
- Software engineering skills (code organisation and readability)
- Quality of documentation and decision-making rationale
- Clarity and thoughtfulness of your write-up
