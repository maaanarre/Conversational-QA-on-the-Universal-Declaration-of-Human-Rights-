# Conversational-QA-on-the-Universal-Declaration-of-Human-Rights-

This demonstrates how to build a **Question Answering system** over the Universal Declaration of Human Rights using [LangChain](https://www.langchain.com/).  
It includes both:
- A **basic RetrievalQA chain** (no memory).
- A **ConversationalRetrievalChain** with memory, enabling follow-up questions.

## Features used
- Load and index the UDHR text into a retriever.
- Ask direct questions about specific articles.
- Compare answers **with vs. without chat memory**.
- Custom prompt designed for **legal/rights context**.
