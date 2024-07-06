---
sidebar_position: 1
sidebar_label : 'Web scraper'
title: ''
---
## Introduction to Web scraper tool

SimplAI provides a powerful and easy-to-use tool for scraping website content, making it an invaluable resource for tasks like Q&A, research, and context generation. This guide will walk you through using SimplAI's `Web Scraper` tool.

## How to Use the Web Scraper Tool

### Adding the Component

First, add the `Web Scraper` step to your Tool. (Refer to our guide on getting started with create a tool for detailed instructions.)

![WS1.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/5d814045-474c-466f-aff1-1b95cbe4ab7b/WS1.png)

### Website URL

Enter the URL you want to scrape directly into the provided box. You can also use the `{{ }}` syntax to activate variable mode. For example, if the URL is stored in an input component called my_url, you would enter `{{my_url}}`.

![WS2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/48e11f1f-a759-4a7e-a882-874c3dc38cdd/WS2.png)

### Guardrails Configurations

SimplAI offers robust guardrails validators to ensure the quality and safety of the extracted content. You can configure these guardrails to suit your needs:

- **Competitor Mentions**: Detects and flags any mentions of competitors in the extracted content.
- **Detection of Personally Identifiable Information (PII)**: Identifies and flags PII to protect sensitive data.
- **Gibberish Text Detection**: Filters out nonsensical or irrelevant text.
- **Toxic Language Detection**: Detects and flags any toxic or harmful language to maintain content quality.
    
    ![WS3.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/30c482d3-3a1f-4931-a883-cfdc07ec214f/f8729d25-3ede-44f5-b51a-17d001cf0f82/WS3.png)
    

These guardrails can be easily integrated into your scraping process, ensuring that the extracted data meets your quality and compliance standards.

For more details on configuring your steps, see the following guides:

1. How to run a step
2. How to delete a step
3. How to configure output
4. How to configure a default output
5. How to move a step in a Tool
6. How to add condition to a step (e.g., execute only if a condition is met)
7. How to loop a step (e.g., run a step multiple times)

## Common Errors

### Wrong URL Formatting

This error occurs when the URL field is not a string. Ensure that when using the output of another step, you access the URL field correctly.

### Non-array Elements

When specifying elements to be scraped, ensure you use + Add new for multiple elements. Avoid leaving an empty list after clicking the button; remove any extra lines using the x icon on the right.

### Invalid URL

This error occurs when the provided URL is not valid. The error message will state: "Protocol error (Page.navigate): Cannot navigate to invalid URL."

### Network Issue

This error typically arises from network problems. Ensure your connection is stable, refresh the page, and try again. The error message will read: "Navigation failed because browser has disconnected!"

### Timeout

This happens when the navigation timeout exceeds 30000 ms. Ensure the page loads within the specified time.