---
sidebar_position: 3

---
# Long text input
The Long Text Input component in SimplAI allows users to enter or upload multiple lines of text. This feature is ideal for capturing extended responses, transcriptions, and other lengthy textual data.

**When to Use**

Utilize the Long Text Input component for scenarios requiring detailed text input, such as:

- User responses
- Audio transcriptions
- Descriptive data entries

**Adding Long Text Input to Your Custom Tool**

The Long Text Input component is found under the User Inputs section. You can add it to your Tool from the user inputs section.

![Screenshot 2024-06-28 at 22.11.35.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/50d926f4-250f-4080-8cd2-4b0e9689c701/Screenshot_2024-06-28_at_22.11.35.png)

**Settings and Configuration**

- **Input name:** Assign a title to your input name component to define its purpose.
- **Description:** Provide a description explaining the intended use or context of the input.
- **Variable Name:** Located at the bottom left, marked in pink, this can be renamed for easy reference within your Tool.

![Screenshot 2024-06-28 at 22.09.29.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/33ce829d-ca9b-4ffc-ad26-978d38ba8eb2/Screenshot_2024-06-28_at_22.09.29.png)

**Accessing the Entered Text**

To access the text entered in this component, use the variable mode `{{}}` along with the input step name. By default, it is accessible via `{{input_0}}`