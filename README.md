# AI User Story Assistant

## Overview
This is a lightweight AI-powered tool that converts raw business requirements into structured user stories and acceptance criteria.

## Problem
Product teams often receive unstructured stakeholder input, which leads to ambiguity, rework, and delays in backlog readiness.

## Solution
This tool uses LLM-based prompt engineering to transform raw input into:
- User Stories
- Acceptance Criteria
- Edge Cases

## Example Input
"Users should be able to track orders easily"

## Example Output
User Story:
As a customer, I want to track my order status so that I can know when it will arrive.

Acceptance Criteria:
- User can view order status
- Status updates in real-time
- Notifications are sent on status changes

## Tech Stack
- Python
- OpenAI API
- Prompt Engineering

## How It Works
The system takes raw input and structures it using a predefined prompt template optimized for Agile delivery.

## Future Improvements
- UI (React)
- Integration with Jira / ADO
- Feedback loop for improving outputs
