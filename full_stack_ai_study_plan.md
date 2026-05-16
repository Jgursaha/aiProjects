# Full-Stack AI Engineering Study Plan

This plan organizes courses covering the core pillars of AI development (LangChain, Anthropic, NVIDIA Infrastructure, and Open-Source ecosystems) into a comprehensive learning progression, culminating in the Claude Certified Architect exam and advanced multi-agent development. 

The schedule assumes a pace of **2-3 courses per week**, starting on Monday, May 4th, 2026. 

---

## Part 1: LangChain & LangSmith Academy

### Week 1: The Basics
*Focus: Get hands-on quickly with the core tools.*
- [x] **May 04, 2026:** Quickstart: LangSmith Essentials
  - *Mini-Project 1 (Tracing):* Write a simple Python script that makes an LLM call, and configure it to send traces to LangSmith. Review the trace latency, input/output, and token usage in the UI.
  - *Mini-Project 2 (Evaluations):* Create a small dataset (5 Q&A pairs) in the LangSmith UI, and write an evaluation script to automatically score an LLM's answers against your dataset.
- [x] **May 06, 2026:** Quickstart: LangChain Essentials - Python
  - *Mini-Project 3 (LCEL):* Build a custom chain using LangChain Expression Language (LCEL) combining a Prompt Template, an LLM, and a structured Output Parser.
  - *Mini-Project 4 (Basic RAG):* Create a simple pipeline that reads a local text file, chunks it, stores it in an in-memory vector store, and answers user questions based on the file.
- [ ] **May 08, 2026:** Quickstart: LangChain Essentials - TypeScript *(Optional)*

### Week 2: LangGraph & Fleet Quickstarts
*Focus: Learn the basics of agentic workflows and no-code tools.*
- [ ] **May 11, 2026:** Quickstart: LangGraph Essentials - Python
- [ ] **May 13, 2026:** Quickstart: LangGraph Essentials - TypeScript *(Optional)*
- [x] **May 15, 2026:** Quickstart: LangSmith Fleet

### Week 3: Core Foundations
*Focus: Deepen your understanding of LangChain and agent reliability.*
- [ ] **May 18, 2026:** Foundation: Introduction to LangChain - Python
- [ ] **May 21, 2026:** Foundation: Building Reliable Agents

### Week 4: Observability & Production
*Focus: Learn how to evaluate, test, and monitor agents in the real world.*
- [ ] **May 25, 2026:** Foundation: Introduction to Agent Observability & Evaluations
- [ ] **May 28, 2026:** Foundation: Monitoring Production Agents

### Week 5: LangGraph Deep Dive & First Project
*Focus: Master LangGraph and build your first full multi-agent application.*
- [ ] **Jun 01, 2026:** Foundation: Introduction to LangGraph - Python
- [ ] **Jun 04, 2026:** Project: Ambient Agents with LangGraph

### Week 6: Advanced Projects & Hands-on Capstone
*Focus: Implement complex, long-running agentic systems and build your first custom A2A workflow.*
- [ ] **Jun 08, 2026:** Project: Deep Agents
- [ ] **Jun 11, 2026:** Project: Deep Research with LangGraph
- [ ] **Custom Capstone 1: Multi-Agent Coding Squad:** Build a LangGraph app where a PM Agent, Developer Agent, and Reviewer Agent collaborate to write code autonomously.

---

## Part 2: Anthropic Academy

### Week 7: AI Fluency & Basics
*Focus: Understand the core capabilities of AI and Claude.*
- [ ] **Jun 15, 2026:** AI Capabilities and Limitations
- [ ] **Jun 17, 2026:** AI Fluency: Framework & Foundations
- [ ] **Jun 19, 2026:** Claude 101

### Week 8: Developer Workflows with Claude Code
*Focus: Integrate Claude Code directly into your development processes.*
- [ ] **Jun 22, 2026:** Claude Code 101
- [ ] **Jun 24, 2026:** Introduction to Claude Cowork
- [ ] **Jun 26, 2026:** Claude Code in Action

### Week 9: Advanced Agent Interactions & Safety Capstone
*Focus: Expand Claude's capabilities using skills, subagents, and implement strict safety rails.*
- [ ] **Jun 29, 2026:** Introduction to agent skills
- [ ] **Jul 01, 2026:** Introduction to subagents
- [ ] **Custom Capstone 2: The "Safe Terminal" (HITL):** Use LangGraph or LangSmith Fleet to wrap your `mcp-sandbox` in a strict "Human-in-the-Loop" gateway, requiring your manual approval before terminal execution.

### Week 10: Building with the Claude API
*Focus: Connect to and build upon Anthropic's models.*
- [ ] **Jul 06, 2026:** Building with the Claude API
- [ ] **Jul 08, 2026:** Claude with Amazon Bedrock
- [ ] **Jul 10, 2026:** Claude with Google Cloud's Vertex AI

### Week 11: Model Context Protocol (MCP)
*Focus: Master the standardized protocol for giving AI access to your data and tools.*
- [ ] **Jul 13, 2026:** Introduction to Model Context Protocol
- [ ] **Jul 16, 2026:** Model Context Protocol: Advanced Topics

### Week 12: Specialized AI Fluency Tracks (Choose Your Path)
*Focus: Tailored applications of AI across different disciplines.*
- [ ] **Jul 20, 2026:** AI Fluency for educators *and* Teaching AI Fluency
- [ ] **Jul 22, 2026:** AI Fluency for students
- [ ] **Jul 24, 2026:** AI Fluency for nonprofits

---

## Part 3: Certification Preparation

### Week 13: Claude Certified Architect Prep
*Focus: Review and prepare for the official certification exam.*
- [ ] **Jul 27, 2026:** Review Exam Domains and Exam Guide (claudecertifications.com)
- [ ] **Jul 29, 2026:** Complete Practice Questions and review Anti-Patterns
- [ ] **Jul 31, 2026:** Take the Claude Certified Architect Exam!

---

> [!TIP]
> **Customizing Your Plan**: For Week 12, pick the tracks that are most relevant to you and skip the others. Similarly, if you don't use AWS or Google Cloud, you can skip the Bedrock and Vertex AI courses in Week 10. You can also use the free community resources at `claudecertifications.com` for extra practice before your exam.

---

## Part 4: Expanding the AI Universe (Future Horizons)

*These areas are explicitly scoped for **after** you complete Part 1-3. Do not tackle these until you have built a solid foundation with LangChain, Anthropic, and achieved your certification.*

### Week 14: The Data Layer (Advanced RAG) & Memory Capstone
*Focus: Mastering how AI retrieves and interacts with massive knowledge bases.*
- [ ] **Explore Vector Databases:** Understand the differences between Pinecone, Milvus, Qdrant, and local options like Chroma.
- [ ] **Advanced Retrieval Techniques:** Study Hybrid Search (combining keyword and vector search), Semantic Chunking, and Re-ranking models (like Cohere).
- [ ] **Custom Capstone 3: The "Memory Bank":** Set up a local Vector Database (like Chroma), embed your local notes and project files, and give your Universal Assistant long-term memory via MCP.

### Week 15: The Open-Source Ecosystem & Hugging Face
*Focus: Navigating the central hub of open-source AI models and datasets.*
- [ ] **Hugging Face Hub:** Learn to navigate the model hub, find datasets, and use Hugging Face Spaces.
- [ ] **Transformers Library:** Understand the basics of downloading and running models directly from the `transformers` library.

### Week 16: Model Customization & Fine-Tuning
*Focus: Altering a model's internal weights to teach it highly specific tasks.*
- [ ] **Fine-Tuning Basics:** Understand the difference between prompting/RAG and Fine-Tuning.
- [ ] **PEFT & LoRA/QLoRA:** Study Parameter-Efficient Fine-Tuning techniques that allow you to fine-tune models on consumer hardware without massive GPU clusters.

### Week 17: Multimodality
*Focus: Moving beyond text to interact with vision, audio, and video.*
- [ ] **Vision Models:** Learn how to pass images to multimodal models (like Claude 3.5 Sonnet or GPT-4o) for analysis.
- [ ] **Audio & Speech:** Explore transcription models (like OpenAI Whisper) and Text-to-Speech (TTS) pipelines to give your agents a voice.
