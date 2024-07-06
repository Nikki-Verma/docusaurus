---
sidebar_position: 1
sidebar_label : 'Introduction to Tool Steps'
title: ''
---

## Introduction to Tool Steps

Tool steps are specific actions or functions that an AI agent can perform on given inputs. They are designed to automate complex workflows, process various types of data, and deliver precise outputs. Each tool step is tailored to handle specific tasks, making AI agents more versatile and effective.

### Examples of Tool Steps

- **LLM Step:** Summarizes an input text using advanced language models.
- **PDF-to-Text Step:** Extracts text from an uploaded PDF file.
- **Python Step:** Executes a Python code snippet for custom data processing.

SimplAI supports a variety of analysis steps, with all requirements taken care of. All you need to do is add the appropriate step component to your tool.

### Adding a Tool Steps

To start creating a tool, navigate to the Tools page. Once there, click on `+ Create tool` in the top right corner. You will be presented with an interface where you can add your tool steps in the `User Steps` section.

![Screenshot 2024-06-28 at 22.48.30.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/e723a77b-bf99-4595-90b3-33687968a98b/Screenshot_2024-06-28_at_22.48.30.png)

### General Tool Step Features

**Run a Step**

To execute a step, click the `Run` button in the top right corner of the tool step. The results will be displayed below each tool step.

There are two options available:

1. Run the tool step only. This option is available at every right side of every tool step.
    
    ![TS1.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/3a1e746b-b500-468c-84ad-7968bc127584/TS1.png)
    
2. Rerun from the top, including the current step. This option is available at the top right corner of the tools page.
    
    ![TS2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/0308276f-68ce-43c4-a01a-01a54e5478e5/TS2.png)
    

**Delete a Step**

To remove a specific tool from a user step, click the settings button in the top right corner of the tool step and select `Remove`. This action will completely delete the tool from the user step.

![TS3.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/a4f163dc-7332-4e70-a12c-0e24c338e71f/TS3.png)

**Run a Step if a Condition is Met**
To run a step only when a condition is met, click on the settings button on the top right corner and select `Enable conditions`.

![TS5.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/96a19f49-406d-4c3b-b980-5d437adc5b16/TS5.png)

Conditions must follow JavaScript rules and be written in `{{}}`.

For example:

1. `{{text==="XYZ"}}` --> the variable called `text` is equal to `XYZ`.
2. `{{text!=="XYZ"}}` --> the variable called `text` is not equal to `XYZ`.
3. `{{clean.transformed===""}}` --> the output of a code step called `clean` is an empty string.

**Run a Step Multiple Times in a Loop**
To run a step multiple times, click on the settings button in the top right corner and select **`Enable foreach`**.

![TS4.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/ea89011a-eac9-44c1-aba8-9bbcd87a2510/TS4.png)

For example, if you have a list of movie names and want to generate a summary for each one using a large language model, use `Enable foreach` option. Under `foreach`, provide the list of items on which the loop should work.

![US9.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/74c2ec29-09c3-4f9e-a769-261e65635dbe/US9.png)