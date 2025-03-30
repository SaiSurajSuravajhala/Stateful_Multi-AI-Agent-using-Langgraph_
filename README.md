# Stateful Multi-Agent System using LangGraph

This project demonstrates a stateful multi-agent system built with LangGraph, a framework for orchestrating AI agents. The system allows multiple agents to maintain and update their internal state over continuous interactions, enabling rich, context-aware communication and coordinated task execution.

## Overview

The notebook shows how to:
- Instantiate stateful agents using LangGraph.
- Maintain and update each agent's state across multiple conversational turns.
- Enable inter-agent communication for collaborative task execution.
- Integrate natural language understanding to process user inputs and generate dynamic responses.

## Key Features

- **Stateful Agents:** Each agent retains context and state, allowing for more human-like, continuous dialogue.
- **Inter-Agent Communication:** Agents exchange information to coordinate responses and handle complex tasks.
- **Dynamic Coordination:** The system showcases how distributed agents can work together in real-time, adapting to new inputs.
- **Modular Architecture:** Easily extend or modify individual agents without affecting the overall system.

## Setup and Requirements

- **Python Version:** 3.8+
- **Dependencies:**
  - LangGraph (for agent orchestration)
  - Transformers (for language processing, if applicable)
  - Additional libraries as specified in `requirements.txt`

To install dependencies, run:
```bash
pip install -r requirements.txt
