# What is LangChain?

LangChain is an open source orchestration framework for the development of applications using large language models (LLMs). LangChain's tools and APIs simplify the process of building LLM-driven applications like chatbots and virtual agents. 

![LangChain Use Cases](./images/what_is_langchain.png)

- **Models:** LangChain supports a variety of different models, so 
you can choose the one that suits your needs best.
  ![LangChain Use Cases](./images/models.png)

  - Language Models are used for generating text
    - LLMs utilize APIs that take input text and 
generate text outputs 
    - ChatModels employ models that process 
chat messages and produce responses.
  - Text Embedding Models convert text into 
numerical representations
    - Text Classification Models categorize text
    - Text Similarity Models compare text
    - Text Generation Models create new text
    - Text Summarization Models create summaries
    - Text Translation Models convert text from one

- **Prompts:** Prompts are the instructions that you give to the LLM. Prompts instruct the LLM to do what you want it to do, and how you want it to do it. Prompts can take the form of a _string_ (for Language Models) or a _list_ of messages (for Chat Models).

  ![LangChain Use Cases](./images/prompts.png) 
    
- **Agents:** LangChain's Agent modules are designed to integrate with existing workflows and systems. They can be used to automate tasks, provide information, and interact with users. They handle things like _parsing input_, _generating output_ and determining the sequence of actions to follow and tools to use.
  ![LangChain Use Cases](./images/agents.png)
- **Chains**: LangChain's Chain modules are used to orchestrate the flow of data and actions between different models and agents. They can be used to _chain together multiple models_, _manage the flow of data_, and _handle the orchestration of tasks_.
  ![LangChain Use Cases](./images/chains_02.png)
- **Indexes**: LangChain's Index modules are used to store and manage data. They can be used to _store and retrieve data_, _manage data storage_, and _index and search data_.
- **Document Loaders**: LangChain's Document Loader modules are used to load and manage documents and data. They can be used to _load and manage documents_, _extract information from documents_, and _store and retrieve documents_.



## **LangChain Use Cases**

![LangChain Use Cases](./images/langchain_usecases.png)

- **Chatbots:** Chatbots are among the most intuitive uses of LLMs. LangChain can be used to provide proper context for the specific use of a chatbot and to integrate chatbots into existing communication channels and workflows with their own APIs.

- **Summarization:** Language models can be tasked with summarizing many types of text, from breaking down complex academic articles and transcripts to providing a digest of incoming emails.

- **Question Answering:** Using specific documents or specialized knowledge bases (like Wolfram, arXiv, or PubMed), LLMs can retrieve relevant information from storage and articulate helpful answers. If fine-tuned or properly prompted, some LLMs can answer many questions even without external information.

- **Data Augmentation:** LLMs can be used to generate synthetic data for use in machine learning. For example, an LLM can be trained to generate additional data samples that closely resemble the data points in a training dataset.

- **Virtual Agents:** Integrated with the right workflows, LangChain’s Agent modules can use an LLM to autonomously determine next steps and take action using robotic process automation (RPA).

References
- [LangChain](https://python.langchain.com/docs/get_started/introduction)