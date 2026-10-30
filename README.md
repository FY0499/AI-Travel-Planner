# AI Travel Planner

I built this AI travel planner with n8n to collect trip preferences, gather information from external APIs, and prepare a personalized itinerary that can be sent by email.

<img width="1144" height="228" alt="AI Travel Planner demo" src="https://github.com/user-attachments/assets/ef949b47-d279-41dd-a8ab-4d0cebe6ee90" />

## How it works

1. The user shares trip details such as destination, dates, budget, number of travelers, and interests.
2. The AI agent organizes the trip information and asks for missing details.
3. The workflow retrieves location, weather, and places information through APIs.
4. The itinerary agent prepares the travel plan.
5. The final result is formatted and sent to the user's email.

## Main features

- Conversational collection of travel preferences.
- Location and weather information.
- Places and points-of-interest lookup.
- AI-generated travel itinerary.
- Email delivery of the final plan.

## Technologies

n8n, Google Gemini, HTTP Request, external APIs, JavaScript, and Gmail.

## Setup

Import [workflow.json](./workflow.json) into n8n, configure the required API keys and credentials, then test the chat and email flow.
