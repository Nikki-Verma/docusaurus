---
sidebar_position: 3
sidebar_label : 'Knowledge base'
title: ''
---
Process your uploaded datasets using SimplAI’s Knowledge Base section, employing various techniques like chunking, vector database, embedding, re-ranking, and retrieval testing.

### What is Knowledge Base Processing?

Knowledge base processing involves organizing and refining your data to make it useful and accessible to your tools and agents. This includes breaking down data into manageable chunks, embedding data for efficient retrieval, storing the data into vector database, and testing retrieval performance.

### Creating a Knowledge Base

1. **Navigate to the Knowledge Base Page:**
    - Log in to [SimplAI](https://app.simplai.ai/re-login).
    - From the main dashboard, go to the `Knowledge Base` section.
        
        ![KB1.png](https://media-simplai.s3.amazonaws.com/KB1.png)
        
2. **Create a New Knowledge base**
    - Go to `+ Create Knowledge Base` on the top right section of the page.
    
    ![KB2.png](https://media-simplai.s3.amazonaws.com/KB2.png)
    

    - Provide a name and description to the Knowledge Base
        
        ![KB3.png](https://media-simplai.s3.amazonaws.com/KB3.png)
        

3. **Selecting KB type**

    In the `Create Knowledge Base` section, choose the `KB type` based on whether your data is **Unstructured** or **Structured**. This choice will determine how your data is processed and stored.

    ![KB3.png](https://media-simplai.s3.amazonaws.com/KB4.png)

4. **Default Settings**

    SimplAI provides default settings with predefined parameters to simplify the setup process.

    - Default embedding model and its pre-defined parameters are available for quick setup.
    - SimplAI offers a default vector database selection for optimized performance.

    > This default setting is optimized for general use cases but can be customized if needed.
    > 

    ![Screenshot 2024-06-30 at 17.19.43.png](https://media-simplai.s3.amazonaws.com/KBsdkjsdf5.png)

    You can use this default option or you can use Custom Knowledge Base Settings based on your requirements.

5. **Custom Settings**

    For more control over your knowledge base processing, SimplAI allows customization of various components, including the vector database, embedding model, and re-ranking parameters.

    **Custom Settings Overview:**

    1. **Vector Database:**
        - In the custom setting in `Create Knowledge Base` section, select `Vector DB`.
        - Choose from available Vector Databases based on performance, scalability, and your specific requirements.
    2. **Custom Embedding Model:**
        - In the `Create Knowledge Base` section, select `Deployed Embedding Model`.
        - Choose the embedding model that best fits your data type and use case (e.g., BERT, GPT-3).
        - Configure parameters such as similarity threshold and the number of top K results.
        - Adjust the settings to fine-tune the embedding process for improved accuracy and relevance.
    3. **Re-Ranking:**
        - Access the `Re-Ranking` tool within the `Knowledge Base` section.
        - Choose the re-ranking model that aligns with your data retrieval goals.
        - Define parameters such as the number of top K results to re-rank.

    ![Screenshot 2024-06-30 at 17.20.12.png](https://media-simplai.s3.amazonaws.com/KB5.png)

    **Benefits of Custom Settings:**

    - **Tailored Performance:** Customize settings to match the specific needs of your data and use cases.
    - **Enhanced Control:** Greater flexibility in configuring how data is processed, stored, and retrieved.
    - **Optimized Relevance:** Fine-tuning parameters ensures that the most relevant data is prioritized, improving the overall effectiveness of your knowledge base.

6. **Import file from Dataset**
    - To Import a file from the `Dataset` , go to the `Import from Dataset` section at the top right section of the page.

    ![KB6.png](https://media-simplai.s3.amazonaws.com/KB6.png)

    - Select the `Dataset` you want to import for your Knowledge Base.
        
        ![KB7.png](https://media-simplai.s3.amazonaws.com/KB7.png)
        

7. **Parsing**

    Parsing helps in extracting and structuring data efficiently.

    1. **Basic Parsing:**
        - Access the `Basic Parsing` tool within the `Knowledge Base` section.
        - This uses predefined parsers to extract common data types and structures from your dataset.
    2. **Advanced Parsing:**
        - Navigate to `Advanced Parsing` in the `Knowledge Base` section.
        - Apply the advanced parser to extract all the data types and structures from your dataset.
            
            ![Screenshot 2024-06-30 at 17.18.30.png](https://media-simplai.s3.amazonaws.com/KB9usygd.png)
        

8. **Chunk Setting**

    Chunking is the process of dividing your data into smaller, manageable pieces.

    1. **Access Chunking Tools:**
        - Navigate to the `Knowledge Base` section.
        - Select `Chunking Setting`.
    2. **Choose a Chunking Method**
        - **Automatic Chunking**
            
            Select automatic chunking to let SimplAI automatically divide your data based on predefined settings.
            
            ![KB9.png](https://media-simplai.s3.amazonaws.com/KB9.png)
            
        - **Manual Chunking**
            
            Choose manual chunking to customize how your data is divided. Select from different splitter types and configure parameters to achieve the best chunking for your use case.
            
            ![KB10.png](https://media-simplai.s3.amazonaws.com/KB10.png)
        
3. **Testing Chunks**
    - On the right side of the screen, you can test the chunked data in the `Chunk Preview`.
    - Review which chunks have been split from the original data to ensure they meet your needs.
        
        ![Screenshot 2024-06-30 at 17.17.39.png](https://media-simplai.s3.amazonaws.com/KB11.png)
        

### Retrieval Testing

    Test the performance of your knowledge base to ensure it returns relevant results.

    1. **Configure Retrieval Tests:**
        
        Go to `Retrieval Testing` in your Knowledge Base. 

    ![KB12.png](https://media-simplai.s3.amazonaws.com/KB12.png)

    1. **Run Tests:**
        - Execute retrieval tests to see how well your knowledge base returns relevant results.
        - Analyze test outcomes and refine your processing steps if necessary.
            
            ![KB13.png](https://media-simplai.s3.amazonaws.com/KB13.png)
        

By following these steps, you can efficiently process and manage your knowledge base within SimplAI, ensuring high-quality data retrieval and improved AI application performance.