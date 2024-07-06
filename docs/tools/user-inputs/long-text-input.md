---
sidebar_position: 2
sidebar_label : 'Long Text Input'
title: ''
---
## Long Text Input

The Long Text Input component in SimplAI allows users to enter or upload multiple lines of text. This feature is ideal for capturing extended responses, transcriptions, and other lengthy textual data.

### **When to Use Long Text Input**

Utilize the Long Text Input component for scenarios requiring detailed text input, such as:

- User responses
- Audio transcriptions
- Descriptive data entries

### **Adding Long Text Input to your Tool**

The Long Text Input component is found under the User Inputs section. You can add it to your Tool from the user inputs section.

![US3.png](https://media-simplai.s3.amazonaws.com/US3.png)

### **Long Text Input Configuration**

- **Input name:** Assign a title to your input name component to define its purpose.
- **Description:** Provide a description explaining the intended use or context of the input.
- **Variable Name:** Located at the bottom left, marked in purple, this can be renamed for easy reference within your Tool.
    
    ![US4.png](https://media-simplai.s3.amazonaws.com/US4.png)
    

### **Accessing the Entered Text**

To access the text entered in this component, use the variable mode `{{}}` along with the input step name. By default, it is accessible via `{{input_0}}`