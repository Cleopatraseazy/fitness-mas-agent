# fitness-mas-agent
# Fitness Multi-Agent System

A Multi-Agent System that generates personalized daily fitness 
and nutrition plans using real API data.

## Agents
- Orchestrator Agent: Coordinates all agents and combines output
- Coach Agent: Creates workout plans using ExerciseDB API
- Dietitian Agent: Creates meal plans using USDA FoodData API

## Features
- Adapts workout plan based on detected injuries using Tavily web search
- Adjusts intensity based on fatigue level
- Supports dietary restrictions
- Multi-hop tool use when constraints are encountered

## APIs Used
- ExerciseDB API (RapidAPI)
- USDA FoodData Central API
- Tavily Search API
- Groq API with Llama 3.3

## How to Run
1. Install requirements: pip install langchain groq tavily-python requests
2. Add your API keys
3. Run the notebook cells in order
