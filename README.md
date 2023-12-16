# Retrieval Augmented Generation
RAGs help LLMs by giving them access to external data so that they can generate a response with 
additional context.

# USAGE
You can they think of RAG as LLM with Vector Search.

![image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*WxpDH9L7baCFJqLU-umMlA.png)

Article by: https://medium.com/@thakermadhav/build-your-own-rag-with-mistral-7b-and-langchain-97d0c92fa146

1. Load vector database with encoded documents
2. Encode the query into a vector using sentence transformer
3. Based on the input query retrieve relevant context from the vector database
4. Leverage context along with the query to prompt the LLM.

