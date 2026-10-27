# AI Travel Planner

An n8n AI travel-planning workflow that gathers trip preferences and builds an itinerary using external data sources.

## Setup
1. Import the workflow JSON into n8n once added to this repository.
2. Configure your weather and places API credentials using n8n credentials or environment variables.
3. Reconnect the email node and set the recipient dynamically from the user's request.
4. Test API responses and email delivery before enabling the workflow.

## Security and testing
Do not publish API keys or personal email addresses. This workflow requires credential setup and end-to-end testing.

## Project status
This README documents the project scope and setup expectations. The workflow export must be present in the repository before it can be imported; validate the finished workflow in your own n8n instance before relying on it.
