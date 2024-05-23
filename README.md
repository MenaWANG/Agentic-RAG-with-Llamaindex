# Agentic-RAG-with-Llamaindex

This is my code and studynote for the course [Building Agentic RAG with LlamaIndex](https://www.deeplearning.ai/short-courses/building-agentic-rag-with-llamaindex/) 📚 A super informative and practical course. Highly recommended! 😎 

# ✅ Lesson 1. Tools Calling using a Router Engine

* In standard RAG, LLM are mainlysed used forr synthesis of information only.
* A router engine adds additional functionality which enables LLM to determine whether to implement a Q&A or a summarization query engine/tool based on the question from the user
* See `L1_Router_Engine` notebook & `get_router_query_engine()` function in `utils`

# ✅ Lesson 2. Tool Calling & Infer Parameters

* In this interation, the LLM not only helps choosing the appropriate tool but also infer necessary arguments for execution. 
* The end result is that users get to ask more questions and receive more preciese results. 
* See `L2_Tool_Calling`notebook & `get_doc_tools()` function in `utils`

# ✅ Lesson 3. Multi-steps Agent

* Use AgentRunner to plan and orchestrate multi-step tasks 
* Use AgentWorker to execute the tasks. 
* Human users can 
    * inspect and chat with the agent about its reasoning and responses 💭
    * control the agent in a granular fashion, which also enhances debuggability and steerability of the agent. 🧭

![Agent](image\agentRunner-and-agentWorker.PNG)
