# Multi-Agent Personal Assistant Flow

## Overview
This repository contains a personal assistant example flow built with multi-agents using Langflow. The system uses a coordinated approach where different agents handle specific tasks and an orchestration layer manages the workflow between them.

## Architecture
The flow consists of several interconnected components:

- **Input**: Entry point for user's action item and related context
- **Agent Types**:
  - **Chat Agent**: Manages conversational interactions
  - **Orchestration Agent**: Coordinates between other agents and manages workflow
  - **RAG Agent**: Retrieves relevant info from Astra DB 
  - **Google Docs Agent**: Handles document-related operations with Composio
  - **Gmail Agent**: Handles Gmail-related operations with Composio
 
## Features
- Multi-agent collaboration for complex task handling
- Specialized agents for different domains
- Orchestrated workflow for efficient task routing
- Integration with external tools and services

## Prerequisites
- Langflow installed
- Python 3.8 or higher

## Getting Started
1. Clone this repository
2. Install Langflow if you haven't already
3. Import the flow JSON file into Langflow
4. Configure any required API keys or credentials
5. Run the flow and interact with your personal assistant

## Usage
1. Input relevant text or a Google Doc link in the "Google Doc Link / Meeting Context" component
2. Navigate to the Playground in the top right of your Langflow screen
3. Submit an action item based on the given context (Ex. "Summarize this document", "Draft me an email with key takeaways from this content", etc)
4. Tweak and modify based on responses

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments
- Built with [Langflow](https://github.com/langflow-ai/langflow)
- Build Your Ultimate Personal Assistant with Multi Agents on Langflow [Youtube Video](https://www.youtube.com/watch?v=VUNQVZCxpVM&lc=UgxrwwW98pGZu8o9Sr54AaABAg)
- Blogpost Coming Soon!...
- Inspired by multi-agent AI systems
