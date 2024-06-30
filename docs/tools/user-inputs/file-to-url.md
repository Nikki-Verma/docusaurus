---
sidebar_position: 5

---
# File to URL
### Introduction to File to URL Input

The File to URL input is a crucial component in SimplAI that enables users to upload a file to the cloud and generate a temporary URL for it. This URL can be used in subsequent steps such as audio transcription or PDF-to-Text conversion, providing seamless access to the file's content.

### When to Use the File to URL Component

The File to URL input component is ideal when you need to supply a file as input to another component within your workflow. For example, it can be used as an input for an OCR (Optical Character Recognition) step.

### Adding a File to URL Input to Your Custom Tool

The File to URL input component can be found under the User Inputs section. You can add it to your tool either through the main section or the sidebar.

![Screenshot 2024-06-28 at 22.24.35.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/e678d76f-9e1e-4b77-85b2-0b745bc2b7a3/Screenshot_2024-06-28_at_22.24.35.png)

### Configuring the File to URL Component

- **Title**: Specify the title for your input component.
- **Description**: Provide a brief description of what this input is for or how it will be used.
- **Variable Name**: Located at the bottom left and marked in green, you can rename this variable. This name will be used to access the data in your tool.
- **Optional/Required**: Found at the top right, this setting determines whether the component is mandatory or optional. A required component must be provided before your analysis can commence.
    
    ![Screenshot 2024-06-28 at 22.26.14.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/89d3ffa3-25b3-44f7-8d52-e14c934be440/Screenshot_2024-06-28_at_22.26.14.png)
    

### Accessing the URL

To access the URL output, use the variable mode `{{}}` and the input step name. By default, it can be accessed using `{{file_url}}`.