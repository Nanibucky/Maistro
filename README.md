# Memory Agent

## Overview

The Memory Agent is an AI-powered chatbot designed to save and manage semantic memories within a user profile or a collection. It leverages technologies such as LangChain, LangGraph, and Trustcall to facilitate long-term memory management and task assistance.


Before you run this application in LangGraph Studio, run Docker first !!!!

![https://github.com/Nanibucky/ToDo_Agents/blob/main/source/cover_page.jpg]

![https://github.com/Nanibucky/ToDo_Agents/blob/main/source/cover_page_2.png]






## Features

- **Semantic Memory Management**: Saves semantic memories to a user profile or a collection.
- **Dynamic Memory Updates**: Determines when to save memories dynamically for better user experience.
- **Trustcall Integration**: Uses Trustcall to update and manage memory schemas.
- **ToDo List Management**: Integrates task_mAIstro, an AI assistant that helps manage a ToDo list.
- **Procedural Memory Support**: Allows users to set preferences for task management.
- **Graphical Observation**: Utilizes LangGraph Studio to observe the application in a graphical format.

## Components

1. **User Profile**: 
   - Stores general information about the user, such as name, job, location, interests, and connections.

2. **ToDo List**: 
   - Maintains a list of tasks, including their status, deadlines, solutions, and estimated time to complete.

3. **Instructions**: 
   - Contains user-specified preferences for updating the ToDo list.

4. **LangGraph Studio**: 
   - Provides a graphical interface to observe the application's behavior and memory updates.

## Functionality

### Memory Updates

- **User Profile Updates**: 
  - The agent updates the user's profile when new personal information is provided.

- **ToDo List Updates**: 
  - Tasks are added, modified, or removed based on user interactions. The agent automatically updates the list without requiring explicit permission.

- **Instructions Updates**: 
  - Preferences for updating the ToDo list are stored and used to tailor the agent's behavior.

### Interaction Flow

1. **User Interaction**: 
   - The user interacts with the agent through natural language.

2. **Reasoning**: 
   - The agent carefully analyzes the user's messages to determine if any updates are needed.

3. **Memory Update**: 
   - If necessary, the agent updates the relevant memory component (user profile, ToDo list, or instructions).

4. **Feedback**: 
   - The agent provides feedback to the user, especially when the ToDo list is updated.

### Tools

- **UpdateMemory Function**: 
  - A function used to update the memory components based on the type of information received.

## .env file
   - Create a environment with    OPENAI_API_KEY="Your-openai-api-key"


## Running LangGraph Studio

To observe the application in a graphical format using LangGraph Studio, follow these steps:

1. Ensure Docker is running in the background.
2. Provide the application studio path to LangGraph Studio.
3. Start LangGraph Studio to visualize the application's behavior and memory updates.

## Conclusion

The Memory Agent is designed to be a helpful companion, streamlining task management and personal information tracking. Its ability to adapt and update based on user interactions makes it a powerful tool for managing tasks and personal information efficiently.
