---
sidebar_position: 2

---
# Text Input

The Text Input component allows users to enter a single line of text. This input can be provided directly by the user.

### When to Use the Text Input Component

The Text Input component is ideal for capturing short pieces of text such as questions, names, or topics.

### Adding a Text Input to Your Custom Tool

The Text Input component can be found under the User Inputs section. You can add it to your custom tool from the main section.

<!-- <Image> -->

### Text Input Settings

- **Title**: The title of your input component.
- **Description**: A brief explanation of what the input will be used for.
- **Variable Name**: Located at the bottom left and marked in green, you can rename the variable to access the data within your tool.
- **Optional/Required**: Located at the top right, this setting determines whether the input is optional or mandatory before the analysis can proceed.

<!-- <Image> -->

### Accessing the Entered Text

To access the text entered by the user, use the variable mode `{{}}` and the input step name. By default, it is accessible via `{{text}}`