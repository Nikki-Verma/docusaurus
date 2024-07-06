---
sidebar_position: 3
sidebar_label : 'Numeric input'
title: ''
---
## Numerical Input

Numeric input is a crucial component within SimplAI that allows users to enter numeric values, ensuring they are treated as numbers rather than strings. These values can be input directly by the user or retrieved from an uploaded dataset during a bulk-run.

### When to Use Numeric Input

The Numeric input component is ideal for scenarios requiring numerical analysis or mathematical operations. It is particularly useful when a process needs to be executed multiple times, where the number of executions is specified by the user.

### Adding Numeric Input to your Tool

To add a Numeric input to your custom tool within SimplAI, locate the component under User Inputs. You can then add it to your tool using either the main section or the side-bar.

![US5.png](https://media-simplai.s3.amazonaws.com/US5.png)

### Numeric Input Configuration

1. **Input name:** The title of your input component.
2. **Description:** A description detailing the purpose and usage of the input.
3. **Variable Name:** Found at the bottom left and marked in pink, this can be renamed and used to access the data in your tool.
    
    ![US6.png](https://media-simplai.s3.amazonaws.com/US6.png)
    

**Note:** Ensure the entered value is a number and treat it as such in any code steps.

### Accessing the Entered Number

To access the entered number, use the variable mode `{{}}` along with the input step name. By default, it can be accessed via `{{input_0}}`.