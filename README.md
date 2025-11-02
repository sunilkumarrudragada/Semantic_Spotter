# Semantic_Spotter

# IntelliPolicy: LangChain-based Insurance Q&A System

## Setup
1. Install dependencies: pip install langchain openai chromadb pdfplumber tiktoken
2. Add your `OPENAI_API_KEY` to `.env`.
3. Run the notebook or app.

## Description
This project builds a Retrieval-Augmented Generation (RAG) system using LangChain to answer insurance-related queries based on policy PDFs.

## Example Query
> What does the policy state about suicide or self-inflicted injury?
## Expected Output
> The policy states that no benefits will be paid for any disability that results from willful self-injury or self-destruction, while sane or insane.

