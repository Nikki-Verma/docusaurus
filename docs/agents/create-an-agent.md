---
sidebar_position: 2

---
# Create an Agent
How to create an AI Agent with SimplAI

In this guide, we will walk you through the process of creating AI Agents at SimplAI, equipping them with the necessary tools, and how to communicate with them effectively.

- **Creating Agents:** This involves defining the agent's identity, capabilities, and expected tasks.
- **Using Agents:** Interacting with agents is as simple as chatting in a regular chat window(Workflow).

## Create a New Agent

You can either create a new agent from scratch. Here’s a step-by-step guide to creating an agent from scratch:

1. **Log In**: Access your SimplAI account at [app.simplai.com](https://app.simplai.ai/)
2. **Navigate to Agents**: Go to the 'Agents' section located in the sidebar.
3. **Initiate New Agent Creation**: Click on “+ Create Agent” at the top right corner of the page.
4. **Define Agent Details**: Provide a name and description to your agent.

<!-- <agent navigation video of our platform> -->

## Configuring Your Agent

Once your agent is created, you need to configure several important aspects to ensure it functions as desired. Here are the key steps:

1. **Choose the Deployed LLM Model**
    - Select the LLM (Large Language Model) to be used by the agent.
    - **Advanced Options**: Customize the LLM model with the following settings:
        - **Max Tokens**: Set the maximum number of tokens the model can use.
        - **Top K Sampling**: Define the number of highest probability vocabulary tokens to keep for sampling.
        - **Repeat Penalty**: Penalize repeated sequences in the output.
        - **Min P Sampling**: Set the minimum probability for sampling.
        - **Top P Sampling**: Specify the cumulative probability for token selection.
2. **Base Instruction**
    
    Provide the foundational instructions that will guide the agent’s responses and actions. These instructions should clearly state what you expect the agent to perform.
    
3. **Knowledge Base**
    
    Add a knowledge base that the agent can refer to for accurate information and responses.
    
4. **Tools**
    
    Equip the agent with the necessary tools it will use to perform tasks. These tools can range from web scraping utilities to APIs for various functionalities.
    
5. **Welcome Message**
    
    Craft a welcome message that the agent will use to greet users. This message sets the tone for initial interactions and provides a friendly introduction.
    
6. **Guardrails Validator**
    
    Set up guardrails to ensure the agent operates within specified boundaries. This might include validating inputs and outputs to adhere to ethical guidelines and operational constraints.
    
7. **Save and Test**:
    - After configuring all settings, save your changes.
    - A chat window will appear on the right side of the screen, displaying the welcome message.
    - Begin interacting with the agent to test its responses.
    - If you encounter any issues, revisit the configuration options to make necessary adjustments.

By following these steps, you will have a fully functional AI Agent tailored to your specific requirement