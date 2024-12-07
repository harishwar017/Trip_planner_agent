
# Travel Planning Assistant

This application is an intelligent travel planning assistant built using OpenAI's API. It leverages modular agents to handle specific tasks, including gathering user preferences, creating travel itineraries, optimizing plans, and fetching weather data. 

## Features

- **Dynamic User Interaction**: Understands user input and asks follow-up questions to gather necessary details.
- **Modular Agents**:
  - **Questionnaire Agent**: Collects missing details like city, budget, dates, interests, etc.
  - **Planner Agent**: Creates a detailed travel itinerary.
  - **Optimization Agent**: Refines travel plans based on user constraints.
  - **Weather Agent**: Fetches weather data for the travel destination.

## Host Address
- http://127.0.0.1:8001/frontend/index.html

## to run
- uvicorn main:app --reload --host 127.0.0.1 --port 8001






