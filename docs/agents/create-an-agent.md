---
sidebar_position: 1
sidebar_label : 'Create an Agent'
title: ''
---

## Create an Agent

SimplAI makes it easy to develop intelligent agents tailored to your specific needs.

Follow the below steps to create and configure an agent, equipping them with the necessary tools, and how to communicate with them effectively.

- **Creating Agents:** This involves defining the agent's identity, capabilities, and expected tasks.
- **Using Agents:** Interacting with agents is as simple as chatting in a regular chat window(Workflow).

### Create a New Agent

You can easily create a new agent by following these simple steps:

1. **Log In**: Access your account at [app.simplai.com](https://app.simplai.ai/)
2. **Go to Agents**: Go to the `Agents` section located in the sidebar.
3. **Create a New Agent**: Click on `+ Create Agent` at the top right corner of the page.
4. **Enter Agent Details**: Provide a name and description for your agent.

<!-- <agent navigation video of our platform> -->

### **Configuring Your Agent**

Once your agent is created, you need to configure several important aspects to ensure it functions as desired. Here are the key steps:

1. **Choose the Deployed LLM Model**
    - Select the LLM (Large Language Model) to be used by the agent.
        
        ![A5.png](https://media-simplai.s3.amazonaws.com/A5.png)
        
    - **Advanced Options**: Customize the LLM model with the following settings:
        - **Max Tokens**: Set the maximum number of tokens the model can use.
        - **Top K Sampling**: Define the number of highest probability vocabulary tokens to keep for sampling.
        - **Repeat Penalty**: Penalize repeated sequences in the output.
        - **Min P Sampling**: Set the minimum probability for sampling.
        - **Top P Sampling**: Specify the cumulative probability for token selection.
            
            ![A6.png](https://media-simplai.s3.amazonaws.com/A6.png)
            
2. **Base Instruction**
    
    Provide the foundational instructions that will guide the agent’s responses and actions. These instructions should clearly state what you expect the agent to perform.
    
    ![A10.png](https://media-simplai.s3.amazonaws.com/A10.png)
    
3. **Knowledge Base**
    
    Add a knowledge base that the agent can refer to for accurate information and responses.
    
    ![A7.png](https://media-simplai.s3.amazonaws.com/A7.png)
    
4. **Tools**
    
    Equip the agent with the necessary tools it will use to perform tasks. These tools can range from web scraping utilities to APIs for various functionalities.
    
    ![A8.png](https://media-simplai.s3.amazonaws.com/A8.png)
    
5. **Welcome Message**
    
    Craft a welcome message that the agent will use to greet users. This message sets the tone for initial interactions and provides a friendly introduction.
    
    ![A11.png](https://media-simplai.s3.amazonaws.com/A11.png)
    
6. **Guardrails Validator**
    
    Set up guardrails to ensure the agent operates within specified boundaries. This might include validating inputs and outputs to adhere to ethical guidelines and operational constraints.
    
    ![Screenshot 2024-07-05 at 13.16.29.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/38e24c69-9dc3-40a6-ae76-869962d452f3/Screenshot_2024-07-05_at_13.16.29.png)
    
7. **Save and Test**:
    - After configuring all settings, save your changes.
    - A chat window will appear on the right side of the screen, displaying the welcome message.
    - Begin interacting with the agent to test its responses.
    - If you encounter any issues, revisit the configuration options to make necessary adjustments.

By following these steps, you will have a fully functional AI Agent tailored to your specific requirements.