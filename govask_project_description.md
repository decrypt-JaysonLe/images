# GovAsk Project Description

## 1. Problem Statement
The Australian Government holds credible datasets across all areas of operation. However, it has not yet identified a suitable AI chatbot to form part of its long-term digital strategy. Existing options such as ChatGPT or Gemini fall short of government requirements, particularly around reliability and accuracy, where standards must exceed 90%. The core challenge is not the lack of data but a trustworthy AI system that can access, interrogate, and present this data with the level of trust, accuracy, and accountability that government decision-making demands.

## 2. Proposed Solution
In order to address this challenge, we proudly present an AI chatbot explicitly designed for government use. Delivers accurate, auditable, and transparent answers by working directly with datasets provided by government agencies. Rather than generating speculative responses, it grounds every answer in verified data sources. Its ability to learn from and operate on inserted datasets enables agencies to interrogate their information conversationally and trust that the insights they receive are reliable and accountable.

## 3. Technology Stack
- **Large Language Model:** Llama 3 8B Instruct  
- **Front-End Development:** Next.js, TailwindCSS, Streamlit UI  
- **Back-End Development:** Python  
- **Data Management:** Vector database for indexing and storing embeddings, enabling fast and accurate retrieval of relevant data  

## 4. Key Features
Key features of GovAsk:
- **Conversational Data Interrogation:** Allows staff to ask natural-language questions across multiple government datasets without needing advanced technical skills  
- **Grounded Responses Only:** GovAsk will give answers based on what it has learnt from the datasets inserted into itself  
- **Auditability and Transparency:** Each interaction produces an audit trail, showing the data used and the reasoning steps taken, ensuring accountability  
- **Ethical and Secure by Design:** Built with strict attention to privacy, fairness, and transparency in algorithmic decision-making  
- **Guided Question Scaffolding:** Offers prompts and suggestions to help users refine their queries and reach meaningful insights faster  

## 5. Example
Users can ask GovAsk questions relating to the datasets they inserted into GovAsk:

![Related question case](https://raw.githubusercontent.com/decrypt-JaysonLe/images/refs/heads/main/Correct%20answer%201.png)

When GovAsk runs, it will look through the dataset and search whether this question include the information in the dataset or not and GovAsk will return an answer like this:

![GovAsk answer for related question](https://raw.githubusercontent.com/decrypt-JaysonLe/images/refs/heads/main/Correct%20answer%202.png)

Meanwhile, GovAsk will refuse to answer questions that do not relate to the datasets:

![Unrelated question case](https://raw.githubusercontent.com/decrypt-JaysonLe/images/refs/heads/main/Wrong%20answer%201.png)

If GovAsk can not find related information for the question, it will reply with the most similar information based on the dataset:

![GovAsk answer for unrelated question](https://raw.githubusercontent.com/decrypt-JaysonLe/images/refs/heads/main/Wrong%20answer%202.png)

## 6. Impact Statement
By enabling government staff to interrogate datasets reliably and transparently, GovAsk supports evidence-based, accountable decision-making and helps agencies unlock the full value of their data assets while maintaining the highest standards of trust and accuracy.