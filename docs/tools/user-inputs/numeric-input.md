---
sidebar_position: 4

---
# Numeric input

Numeric input is a crucial component within SimplAI that allows users to enter numeric values, ensuring they are treated as numbers rather than strings. These values can be input directly by the user or retrieved from an uploaded dataset during a bulk-run.

### When to Use Numeric Input

The Numeric input component is ideal for scenarios requiring numerical analysis or mathematical operations. It is particularly useful when a process needs to be executed multiple times, where the number of executions is specified by the user.

### Adding Numeric Input to Your Custom Tool

To add a Numeric input to your custom tool within SimplAI, locate the component under User Inputs. You can then add it to your tool using either the main section or the side-bar.

![Screenshot 2024-06-28 at 22.17.34.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/19a7e068-9355-4c2d-9c98-ee6d21c9d7da/Screenshot_2024-06-28_at_22.17.34.png)

### Numeric Input Settings

1. **Input name:** The title of your input component.
2. **Description:** A description detailing the purpose and usage of the input.
3. **Variable Name:** Found at the bottom left and marked in pink, this can be renamed and used to access the data in your tool.

![Screenshot 2024-06-28 at 22.19.22.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/a3d6e363-f9cd-41ac-896d-28976c189bf0/Screenshot_2024-06-28_at_22.19.22.png)

**Note:** Ensure the entered value is a number and treat it as such in any code steps.

### Accessing the Entered Number

To access the entered number, use the variable mode `{{}}` along with the input step name. By default, it can be accessed via `{{number}}`.