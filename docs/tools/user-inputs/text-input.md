---
sidebar_position: 1
sidebar_label : 'Text Input'
title: ''
---
## Text Input

The Text Input component allows users to enter a single line of text. This input can be provided directly by the user.

### When to Use the Text Input

The Text Input component is ideal for capturing short pieces of text such as questions, names, or topics.

### Adding a Text Input to your Tool

The Text Input component can be found under the User Inputs section. You can add it to your custom tool from the main section.

![US1.png](https://media-simplai.s3.amazonaws.com/US1.png)

### Text Input Configuration

- **Title**: The title of your input component.
- **Description**: A brief explanation of what the input will be used for.
- **Variable Name**: Located at the bottom left and marked in purple, you can rename the variable to access the data within your tool.

![US2.png](https://media-simplai.s3.amazonaws.com/US2.png)

### Accessing the Entered Text

To access the text entered by the user, use the variable mode `{{}}` and the input step name. By default, it is accessible via `{{input_0}}`