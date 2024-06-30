---
sidebar_position: 1

---
# Get started

# User Inputs - Getting Started with SimplAI

To perform data analysis or pass instructions to a Tool, user inputs are essential. These inputs serve various purposes, such as:

1. Providing settings and instructions (e.g., specifying the maximum number of items to extract, formatting guidelines for the output)
2. Supplying actual data for analysis (e.g., uploading a CSV file)
3. Posing questions to be answered

### Creating a Tool and Adding User Inputs

The easiest way to begin creating a Tool is to navigate to the Tools page. Once there, click on the "+ Create Tool" button located at the top right corner of the page.

You will be greeted with an empty state where you can:

![Screenshot 2024-06-28 at 10.10.37.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/90bf86e3-0185-40d8-95cb-bb832a782365/Screenshot_2024-06-28_at_10.10.37.png)

1. Add inputs
2. Add tool steps

In the following sections, we will explore all the supported user inputs in SimplAI.

**Hint:**

> Variables are used to reference user inputs within Tools. Variable names can be accessed using double curly braces `{{}}` . For example, to use the value from a text input named `my_text_input`, you would reference it as `{{my_text_input}}`.
>