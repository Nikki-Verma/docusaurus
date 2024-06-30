---
sidebar_position: 2

---
# Create a Tool

# Create a Tool - Step 1

Getting Started with Your First Tool

### Creating a Tool

The easiest way to begin creating a tool is by navigating to the Tools page. Once there, click on the "+ Create Tool" button located at the top right of the page.

You will see an empty template where you can:

1. User inputs
2. User Steps
3. Tool Output
    
    ![Screenshot 2024-06-28 at 19.52.42.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/5d9d3f3d-71ed-4d79-9b4f-3f59d8307242/Screenshot_2024-06-28_at_19.52.42.png)
    

### User Inputs

Every tool requires inputs. Inputs are used to pass data or instructions on how to analyze the data within the tool.

To add inputs, go to the "User Inputs" section. SimplAI offers a variety of input types and manages all the necessary steps.

### User Steps

Steps are the analytical components of your tool. SimplAI provides a range of steps, from simple LLM models to more complex tasks like knowledge search and API calls.

To add user steps, click on the `+ Add User Step` button. For more details on the available steps, visit the User Steps.

### Example(made the changes)

1. On your Tools page, click on "+ Create Tool" and then add your "Tool Name” and “Tool Description”. Once these steps are done, a User Input component will appear on the page. Choose “+ Text” in the User input step. Next steps:
    1. Add a Input name (optional)
    2. Add a description (optional)
    3. Add test value (optional)
    4. Change the variable name (shown in pink) from "input_0" to "topic." This variable name will be used later in the User Steps.
        
        ![Screenshot 2024-06-28 at 20.22.11.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/98946fa9-3a86-4a1f-ad18-a456e56588b3/Screenshot_2024-06-28_at_20.22.11.png)
        
    
2. Click on `+ Add User Step` and select `LLM call` from the options. This adds an LLM component to your tool. We will experiment with text generation using LLMs like GPT.
3. Write your prompt (i.e., your instructions for the large language model) in the Prompt section of the “LLM call” step.
4. Save your tool by clicking the "Save Tool" button at the top right.
5. Run your tool. You can do this by clicking the "Run Tool" button at the top right on the current page. Enter your text in the user input component, which will be used in the prompt.

Click "Run once" on the App page or the run icon on the Build page in the LLM step to see the LLM output. In my execution, GPT-3.5 generated the following: