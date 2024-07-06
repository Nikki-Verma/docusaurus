---
sidebar_position: 4
sidebar_label : 'File to URL'
title: ''
---
## File to URL Input

The File to URL input is a crucial component in SimplAI that enables users to upload a file to the cloud and generate a temporary URL for it. This URL can be used in subsequent steps such as audio transcription or PDF-to-Text conversion, providing seamless access to the file's content.

### When to Use the File to URL Component

The File to URL input component is ideal when you need to supply a file as input to another component within your workflow. For example, it can be used as an input for an OCR (Optical Character Recognition) step.

### Adding a File to URL Input to Your Custom Tool

The File to URL input component can be found under the User Inputs section. You can add it to your tool either through the main section or the sidebar.

![US7.png](https://media-simplai.s3.amazonaws.com/US7.png)

### Configuring the File to URL Component

- **Title**: Specify the title for your input component.
- **Description**: Provide a brief description of what this input is for or how it will be used.
- **Variable Name**: Located at the bottom left and marked in purple, you can rename this variable. This name will be used to access the data in your tool.

![US8.png](https://media-simplai.s3.amazonaws.com/US8.png)

### Accessing the URL

To access the URL output, use the variable mode `{{}}` and the input step name. By default, it can be accessed using `{{input_0}}`.