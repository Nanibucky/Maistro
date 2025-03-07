# Memory Agent

![Chatbot Interface][https://github.com/Nanibucky/ToDo_Agents/blob/main/Source/LangGraph_record.mp4]



## Overview

The Memory Agent is an AI-powered chatbot designed to save and manage semantic memories within a user profile or a collection. It integrates LangChain, LangGraph, and Trustcall to facilitate long-term memory retention and procedural adaptation.

## Features

Saves semantic memories to a user profile or a collection.

Uses Trustcall to update and manage memory schemas.

Integrates task_mAIstro, an AI assistant that helps manage a ToDo list.

Supports procedural memory, allowing users to set preferences for task management.

Determines when to save memories dynamically for better user 




# Memory Agent

## Overview

The Memory Agent is a sophisticated system designed to assist users by keeping track of their personal information, tasks, and preferences. It leverages long-term memory to provide a personalized and efficient user experience.

## Components

1. **User Profile**: 
   - Stores general information about the user, such as name, job, location, interests, and connections.

2. **ToDo List**: 
   - Maintains a list of tasks, including their status, deadlines, solutions, and estimated time to complete.

3. **Instructions**: 
   - Contains user-specified preferences for updating the ToDo list.

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

## Conclusion

The Memory Agent is designed to be a helpful companion, streamlining task management and personal information tracking. Its ability to adapt and update based on user interactions makes it a powerful tool for enhancing productivity and organization.
