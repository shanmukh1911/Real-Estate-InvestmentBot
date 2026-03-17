# Real Estate InvestmentBot

An AI-driven real estate investment assistant built using a modular agent-based architecture. The system automates property research, financial analysis, and investment recommendations using LLM-powered agents and task orchestration.

## Overview

This project leverages AI agents to simulate real-world real estate analysis workflows. It combines structured reasoning, financial evaluation, and market research to generate data-driven investment insights.

The system is designed to:
- Identify promising real estate investment locations
- Analyze market trends and property metrics
- Estimate ROI and rental yields
- Generate comprehensive investment reports

## Architecture

The system follows a modular agent-based design:

- **Agents**: Specialized AI agents for property research and analysis :contentReference[oaicite:0]{index=0}  
- **Tasks**: Structured workflows defining investment analysis steps :contentReference[oaicite:1]{index=1}  
- **Crew**: Orchestrates agents and tasks into a unified pipeline :contentReference[oaicite:2]{index=2}  
- **Tools**: External tools (e.g., search APIs) used by agents :contentReference[oaicite:3]{index=3}  

### Workflow

1. Property research agent gathers market and location data  
2. Financial and qualitative analysis is performed  
3. Results are compiled into a structured investment report  

## Features

- Agent-based modular architecture  
- Task orchestration for complex reasoning workflows  
- Market analysis including pricing, vacancy, and yield  
- Financial evaluation (ROI, rental yield, risk assessment)  
- Integration with LLMs for reasoning and report generation  
- Extensible design for adding new agents and tools  

## Tech Stack

- Python  
- CrewAI  
- LangChain (Groq LLM integration)  
- Serper API (search tool)  
- Pipenv for dependency management :contentReference[oaicite:4]{index=4}  

## Installation

### Prerequisites
- Python 3.9+
- Pipenv

### Setup

```bash
pip install pipenv
pipenv install
pipenv install langchain_groq
pipenv install crewai
pipenv install crewai_tools
