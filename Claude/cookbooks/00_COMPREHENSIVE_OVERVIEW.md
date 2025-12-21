# Claude Cookbooks: Comprehensive Overview

## Table of Contents
- [Introduction](#introduction)
- [Repository Statistics](#repository-statistics)
- [Categories Overview](#categories-overview)
- [Complete Cookbook Catalog](#complete-cookbook-catalog)
- [Quick Reference by Category](#quick-reference-by-category)

## Introduction

This repository contains **65+ production-ready Jupyter notebooks** demonstrating Claude's capabilities across multiple domains. Each cookbook provides practical, tested implementations that can be adapted for real-world applications.

## Repository Statistics

- **Total Cookbooks**: 65
- **Categories**: 11
- **Integration Partners**: 10+
- **Authors**: 15+
- **Last Updated**: 2025

## Categories Overview

### 1. **RAG & Retrieval** (9 cookbooks)
Advanced retrieval-augmented generation patterns including contextual embeddings, semantic search, and multi-document systems.

### 2. **Tools** (12 cookbooks)
Tool use patterns from basic calculators to advanced programmatic tool calling and memory management.

### 3. **Multimodal** (7 cookbooks)
Vision capabilities including image analysis, chart reading, document transcription, and crop tools.

### 4. **Agent Patterns** (7 cookbooks)
Multi-agent workflows including orchestrator-workers, evaluator-optimizer, and sub-agent patterns.

### 5. **Integrations** (12 cookbooks)
Third-party integrations with LlamaIndex, Pinecone, MongoDB, Deepgram, ElevenLabs, and more.

### 6. **Responses** (9 cookbooks)
Output optimization including JSON mode, batch processing, prompt caching, and citations.

### 7. **Skills** (4 cookbooks)
Excel, PowerPoint, PDF skills for document creation and financial applications.

### 8. **Claude Agent SDK** (3 cookbooks)
Official SDK tutorials for building research agents, multi-agent systems, and MCP integrations.

### 9. **Thinking** (2 cookbooks)
Extended thinking capabilities for transparent step-by-step reasoning with and without tools.

### 10. **Evals** (3 cookbooks)
Evaluation frameworks for measuring and improving Claude's performance.

### 11. **Observability** (1 cookbook)
Usage tracking and cost analysis via Admin API.

### 12. **Fine-Tuning** (1 cookbook)
Fine-tuning Claude 3 Haiku on Amazon Bedrock.

---

## Complete Cookbook Catalog

### 🔍 RAG & Retrieval

#### **Classification with Claude**
- **Path**: `capabilities/classification/guide.ipynb`
- **Purpose**: Build intelligent classification systems for complex categorization tasks
- **Key Features**:
  - RAG-enhanced classification for insurance tickets
  - Chain-of-thought reasoning for accurate categorization
  - Production-ready classifier implementation
- **Use Cases**: Customer support ticket routing, content categorization, risk assessment

#### **Enhancing RAG with Contextual Retrieval**
- **Path**: `capabilities/contextual-embeddings/guide.ipynb`
- **Purpose**: Improve RAG accuracy by 67% using contextual chunk enrichment
- **Key Features**:
  - Context-aware chunk embeddings
  - Prompt caching for cost optimization
  - BM25 hybrid search integration
- **Use Cases**: Enterprise knowledge bases, legal document search, technical documentation

#### **Retrieval Augmented Generation**
- **Path**: `capabilities/retrieval_augmented_generation/guide.ipynb`
- **Purpose**: Comprehensive RAG implementation guide with advanced optimization
- **Key Features**:
  - Summary indexing for large corpora
  - Reranking techniques for precision
  - Multi-stage retrieval pipelines
- **Use Cases**: Question answering systems, research assistants, knowledge management

#### **Summarization with Claude**
- **Path**: `capabilities/summarization/guide.ipynb`
- **Purpose**: Summarize complex legal documents with evaluation metrics
- **Key Features**:
  - Multi-stage summarization pipeline
  - Quality evaluation framework
  - Structured output formatting
- **Use Cases**: Legal document analysis, research paper summarization, news aggregation

#### **Text to SQL with Claude**
- **Path**: `capabilities/text_to_sql/guide.ipynb`
- **Purpose**: Convert natural language to SQL with self-improvement
- **Key Features**:
  - RAG-enhanced schema understanding
  - Chain-of-thought SQL generation
  - Self-correction and validation
- **Use Cases**: Business intelligence tools, data analytics platforms, reporting systems

#### **How to Make SQL Queries with Claude**
- **Path**: `misc/how_to_make_sql_queries.ipynb`
- **Purpose**: Basic natural language to SQL conversion
- **Key Features**:
  - Database schema context injection
  - Simple query generation
  - Error handling patterns
- **Use Cases**: Data exploration, ad-hoc queries, database interfaces

#### **"Uploading" PDFs to Claude Via the API**
- **Path**: `misc/pdf_upload_summarization.ipynb`
- **Purpose**: Process and summarize PDF documents programmatically
- **Key Features**:
  - Text extraction from PDFs
  - Base64 encoding for API
  - Structured summarization
- **Use Cases**: Document management, contract analysis, research paper review

#### **Summarizing Web Page Content with Claude 3 Haiku**
- **Path**: `misc/read_web_pages_with_haiku.ipynb`
- **Purpose**: Fetch and summarize web content efficiently
- **Key Features**:
  - URL content extraction
  - Cost-effective Haiku usage
  - Structured web data processing
- **Use Cases**: News monitoring, competitor analysis, content curation

#### **Citations**
- **Path**: `misc/using_citations.ipynb`
- **Purpose**: Enable detailed source citations for factual verification
- **Key Features**:
  - Automatic source tracking
  - Footnote generation
  - Quote attribution
- **Use Cases**: Research reports, legal briefs, academic writing

---

### 🛠️ Tools

#### **Calculator Tool**
- **Path**: `tool_use/calculator_tool.ipynb`
- **Purpose**: Provide Claude with arithmetic and mathematical capabilities
- **Key Features**:
  - Basic calculator implementation
  - Tool use fundamentals
  - Error handling
- **Use Cases**: Mathematical problem solving, financial calculations, data analysis

#### **Customer Service Agent**
- **Path**: `tool_use/customer_service_agent.ipynb`
- **Purpose**: Build intelligent chatbots with customer data access
- **Key Features**:
  - Customer lookup tools
  - Order management integration
  - Context-aware responses
- **Use Cases**: Support automation, order tracking, customer self-service

#### **Extracting Structured JSON**
- **Path**: `tool_use/extracting_structured_json.ipynb`
- **Purpose**: Extract structured data from unstructured text
- **Key Features**:
  - Schema-based extraction
  - Tool use for JSON generation
  - Validation and error handling
- **Use Cases**: Data extraction, form processing, API integration

#### **Memory & Context Management**
- **Path**: `tool_use/memory_cookbook.ipynb`
- **Purpose**: Build AI agents with persistent memory capabilities
- **Key Features**:
  - Long-term memory storage
  - Context editing and summarization
  - Memory retrieval strategies
- **Use Cases**: Personal assistants, customer relationship management, ongoing projects

#### **Parallel Tool Calls**
- **Path**: `tool_use/parallel_tools.ipynb`
- **Purpose**: Execute multiple tools concurrently for efficiency
- **Key Features**:
  - Batch tool meta-pattern
  - Concurrent execution
  - Result aggregation
- **Use Cases**: Multi-step workflows, data gathering, parallel processing

#### **Tool Choice**
- **Path**: `tool_use/tool_choice.ipynb`
- **Purpose**: Control how Claude selects and uses tools
- **Key Features**:
  - Forced tool selection
  - Auto mode configuration
  - Tool prioritization
- **Use Cases**: Workflow automation, specialized agents, controlled interactions

#### **Tool Use with Pydantic**
- **Path**: `tool_use/tool_use_with_pydantic.ipynb`
- **Purpose**: Create type-safe tools with validation
- **Key Features**:
  - Pydantic model integration
  - Automatic validation
  - Type safety
- **Use Cases**: Production systems, API wrappers, data validation

#### **Vision with Tools**
- **Path**: `tool_use/vision_with_tools.ipynb`
- **Purpose**: Combine vision capabilities with tool use
- **Key Features**:
  - Image analysis with structured output
  - Nutrition label extraction
  - Multi-modal tool integration
- **Use Cases**: Document processing, product analysis, visual data extraction

#### **Programmatic Tool Calling (PTC)**
- **Path**: `tool_use/programmatic_tool_calling_ptc.ipynb`
- **Purpose**: Reduce latency by letting Claude write code that calls tools
- **Key Features**:
  - Code execution environment
  - Dynamic tool orchestration
  - Reduced token consumption
- **Use Cases**: Complex workflows, data pipelines, automation scripts

#### **Tool Search with Embeddings**
- **Path**: `tool_use/tool_search_with_embeddings.ipynb`
- **Purpose**: Scale to thousands of tools using semantic search
- **Key Features**:
  - Embedding-based tool discovery
  - Dynamic tool selection
  - Scalable architecture
- **Use Cases**: Large tool libraries, enterprise platforms, API marketplaces

#### **Automatic Context Compaction**
- **Path**: `tool_use/automatic-context-compaction.ipynb`
- **Purpose**: Manage context limits in long-running workflows
- **Key Features**:
  - Automatic conversation compression
  - Important context preservation
  - Token budget management
- **Use Cases**: Extended conversations, multi-session agents, context-heavy workflows

#### **Tool Evaluation**
- **Path**: `tool_evaluation/tool_evaluation.ipynb`
- **Purpose**: Evaluate tool performance independently
- **Key Features**:
  - Parallel agent evaluations
  - Independent task files
  - Performance metrics
- **Use Cases**: Tool testing, quality assurance, performance optimization

---

### 🖼️ Multimodal

#### **Getting Started with Vision**
- **Path**: `multimodal/getting_started_with_vision.ipynb`
- **Purpose**: Introduction to passing images to Claude
- **Key Features**:
  - Image encoding basics
  - Base64 conversion
  - API integration
- **Use Cases**: Image analysis, visual Q&A, content moderation

#### **Best Practices for Vision**
- **Path**: `multimodal/best_practices_for_vision.ipynb`
- **Purpose**: Optimize image processing performance
- **Key Features**:
  - Image size optimization
  - Prompt engineering for vision
  - Performance tips
- **Use Cases**: Production vision systems, batch image processing, cost optimization

#### **How to Transcribe Documents**
- **Path**: `multimodal/how_to_transcribe_text.ipynb`
- **Purpose**: Extract and structure text from images and PDFs
- **Key Features**:
  - OCR-like extraction
  - Structured output formatting
  - Multi-page document handling
- **Use Cases**: Document digitization, form processing, invoice extraction

#### **Reading Charts, Graphs, and PowerPoints**
- **Path**: `multimodal/reading_charts_graphs_powerpoints.ipynb`
- **Purpose**: Extract insights from visual data representations
- **Key Features**:
  - Chart data extraction
  - Graph interpretation
  - Slide deck analysis
- **Use Cases**: Business intelligence, financial analysis, presentation review

#### **Using Haiku as a Sub-Agent**
- **Path**: `multimodal/using_sub_agents.ipynb`
- **Purpose**: Multi-agent pattern for financial report analysis
- **Key Features**:
  - Haiku for extraction
  - Opus for synthesis
  - Cost-optimized workflow
- **Use Cases**: Document processing pipelines, multi-stage analysis, cost optimization

#### **Crop Tool for Image Analysis**
- **Path**: `multimodal/crop_tool.ipynb`
- **Purpose**: Zoom into image regions for detailed analysis
- **Key Features**:
  - Region-of-interest extraction
  - Detailed sub-image analysis
  - Chart and diagram processing
- **Use Cases**: Complex document analysis, detailed chart reading, precision extraction

#### **Multi-Modal with LlamaIndex**
- **Path**: `third_party/LlamaIndex/Multi_Modal.ipynb`
- **Purpose**: Image understanding using LlamaIndex abstraction
- **Key Features**:
  - Simplified multi-modal API
  - LlamaIndex integration
  - Image reasoning
- **Use Cases**: Visual question answering, image-text alignment, content analysis

---

### 🤖 Agent Patterns

#### **Basic Workflows**
- **Path**: `patterns/agents/basic_workflows.ipynb`
- **Purpose**: Three simple multi-LLM workflow patterns
- **Key Features**:
  - Sequential processing
  - Parallel processing
  - Router pattern
- **Use Cases**: Quality improvement, cost-latency tradeoffs, specialized processing

#### **Evaluator Optimizer**
- **Path**: `patterns/agents/evaluator_optimizer.ipynb`
- **Purpose**: Generation-evaluation feedback loop
- **Key Features**:
  - Generator LLM
  - Evaluator LLM
  - Iterative improvement
- **Use Cases**: Content quality assurance, automated testing, self-improvement

#### **Orchestrator Workers**
- **Path**: `patterns/agents/orchestrator_workers.ipynb`
- **Purpose**: Central orchestrator with specialized workers
- **Key Features**:
  - Dynamic task delegation
  - Worker specialization
  - Result synthesis
- **Use Cases**: Complex multi-domain tasks, team simulation, parallel expertise

#### **Using Haiku as a Sub-Agent**
- **Path**: `multimodal/using_sub_agents.ipynb`
- **Purpose**: Cost-optimized multi-agent pattern
- **Key Features**:
  - Task decomposition
  - Model selection per task
  - Cost efficiency
- **Use Cases**: Budget-conscious workflows, task specialization, hybrid approaches

#### **00 - The One-Liner Research Agent**
- **Path**: `claude_agent_sdk/00_The_one_liner_research_agent.ipynb`
- **Purpose**: Simple autonomous research agent using SDK
- **Key Features**:
  - WebSearch integration
  - Autonomous research
  - Minimal configuration
- **Use Cases**: Quick research tasks, information gathering, fact-checking

#### **01 - The Chief of Staff Agent**
- **Path**: `claude_agent_sdk/01_The_chief_of_staff_agent.ipynb`
- **Purpose**: Advanced multi-agent systems with subagents
- **Key Features**:
  - Subagent orchestration
  - Hooks and output styles
  - Plan mode
- **Use Cases**: Complex project management, multi-domain coordination, strategic planning

#### **02 - The Observability Agent**
- **Path**: `claude_agent_sdk/02_The_observability_agent.ipynb`
- **Purpose**: External system integration via MCP servers
- **Key Features**:
  - MCP server connections
  - GitHub monitoring
  - CI workflow integration
- **Use Cases**: DevOps automation, system monitoring, workflow orchestration

---

### 🔌 Integrations

#### **LlamaIndex - Basic RAG**
- **Path**: `third_party/LlamaIndex/Basic_RAG_With_LlamaIndex.ipynb`
- **Purpose**: Document retrieval and Q&A with LlamaIndex
- **Key Features**:
  - Simple RAG setup
  - Document indexing
  - Query interface
- **Use Cases**: Knowledge bases, document search, Q&A systems

#### **LlamaIndex - Multi-Document Agents**
- **Path**: `third_party/LlamaIndex/Multi_Document_Agents.ipynb`
- **Purpose**: Large document collections with DocumentAgents
- **Key Features**:
  - Per-document agents
  - ReAct pattern
  - Collection-wide search
- **Use Cases**: Library systems, research databases, multi-source analysis

#### **LlamaIndex - ReAct Agent**
- **Path**: `third_party/LlamaIndex/ReAct_Agent.ipynb`
- **Purpose**: Tool-based reasoning and action workflows
- **Key Features**:
  - ReAct loop
  - Tool integration
  - LlamaIndex abstraction
- **Use Cases**: Interactive agents, tool-heavy workflows, research tasks

#### **LlamaIndex - Router Query Engine**
- **Path**: `third_party/LlamaIndex/Router_Query_Engine.ipynb`
- **Purpose**: Route queries to appropriate indices
- **Key Features**:
  - Multi-index routing
  - Query classification
  - Specialized retrieval
- **Use Cases**: Multi-domain systems, specialized knowledge bases, hybrid search

#### **LlamaIndex - SubQuestion Query Engine**
- **Path**: `third_party/LlamaIndex/SubQuestion_Query_Engine.ipynb`
- **Purpose**: Decompose complex queries into sub-questions
- **Key Features**:
  - Query decomposition
  - Parallel sub-query execution
  - Answer synthesis
- **Use Cases**: Complex analytical queries, research questions, multi-faceted analysis

#### **Pinecone - RAG**
- **Path**: `third_party/Pinecone/rag_using_pinecone.ipynb`
- **Purpose**: Vector database integration for semantic search
- **Key Features**:
  - Pinecone vector storage
  - Semantic retrieval
  - Production-ready architecture
- **Use Cases**: Large-scale knowledge bases, production RAG, semantic search

#### **Pinecone - Claude 3 RAG Agents**
- **Path**: `third_party/Pinecone/claude_3_rag_agent.ipynb`
- **Purpose**: Advanced RAG agents with LangChain v1
- **Key Features**:
  - Agent framework
  - Tool integration
  - Conversational RAG
- **Use Cases**: Interactive knowledge assistants, research bots, Q&A agents

#### **MongoDB - RAG**
- **Path**: `third_party/MongoDB/rag_using_mongodb.ipynb`
- **Purpose**: Build chatbot with MongoDB vector search
- **Key Features**:
  - MongoDB Atlas integration
  - Vector search
  - Tech news knowledge base
- **Use Cases**: Knowledge chatbots, document search, content recommendation

#### **Deepgram - Audio Transcription**
- **Path**: `third_party/Deepgram/prerecorded_audio.ipynb`
- **Purpose**: Transcribe audio and generate interview questions
- **Key Features**:
  - Deepgram transcription
  - Claude analysis
  - Question generation
- **Use Cases**: Interview prep, podcast analysis, meeting transcription

#### **ElevenLabs - Voice Assistant**
- **Path**: `third_party/ElevenLabs/low_latency_stt_claude_tts.ipynb`
- **Purpose**: Low-latency voice assistant
- **Key Features**:
  - Speech-to-text
  - Claude processing
  - Text-to-speech
- **Use Cases**: Voice interfaces, conversational AI, accessibility tools

#### **Wolfram Alpha - LLM API**
- **Path**: `third_party/WolframAlpha/using_llm_api.ipynb`
- **Purpose**: Computational queries via Wolfram Alpha
- **Key Features**:
  - Wolfram API integration
  - Mathematical computation
  - Factual queries
- **Use Cases**: Math assistants, scientific computation, data analysis

#### **Wikipedia - Iterative Search**
- **Path**: `third_party/Wikipedia/wikipedia-search-cookbook.ipynb`
- **Purpose**: Research workflows with Wikipedia (legacy)
- **Key Features**:
  - Iterative search
  - Information gathering
  - Claude 2 examples
- **Use Cases**: Research tasks, fact-finding, knowledge exploration

---

### 📝 Responses

#### **JSON Mode**
- **Path**: `misc/how_to_enable_json_mode.ipynb`
- **Purpose**: Reliable JSON output from Claude
- **Key Features**:
  - Prompting techniques
  - Schema enforcement
  - Output validation
- **Use Cases**: API integrations, data extraction, structured outputs

#### **Batch Processing**
- **Path**: `misc/batch_processing.ipynb`
- **Purpose**: Process large volumes with 50% cost reduction
- **Key Features**:
  - Message Batches API
  - Asynchronous processing
  - Cost optimization
- **Use Cases**: Bulk processing, offline workflows, cost-sensitive tasks

#### **Building a Moderation Filter**
- **Path**: `misc/building_moderation_filter.ipynb`
- **Purpose**: Customizable content moderation
- **Key Features**:
  - Rule-based filtering
  - Category definitions
  - Prompt-based configuration
- **Use Cases**: Content platforms, community moderation, safety systems

#### **Prompt Caching**
- **Path**: `misc/prompt_caching.ipynb`
- **Purpose**: Cache context for cost and speed optimization
- **Key Features**:
  - Context reuse
  - Cost savings
  - Latency reduction
- **Use Cases**: Repeated queries, RAG systems, conversational agents

#### **Speculative Prompt Caching**
- **Path**: `misc/speculative_prompt_caching.ipynb`
- **Purpose**: Reduce time-to-first-token with cache warming
- **Key Features**:
  - Predictive caching
  - Latency optimization
  - User experience enhancement
- **Use Cases**: Interactive applications, low-latency systems, predictive UX

#### **Sampling Past Max Tokens**
- **Path**: `misc/sampling_past_max_tokens.ipynb`
- **Purpose**: Generate longer responses beyond limits
- **Key Features**:
  - Prefill technique
  - Message continuation
  - Extended generation
- **Use Cases**: Long-form content, detailed reports, comprehensive answers

#### **Metaprompt**
- **Path**: `misc/metaprompt.ipynb`
- **Purpose**: Generate starting prompts for tasks
- **Key Features**:
  - Prompt engineering tool
  - Task decomposition
  - Blank-page solution
- **Use Cases**: Prompt development, task planning, workflow design

#### **Citations**
- **Path**: `misc/using_citations.ipynb`
- **Purpose**: Source verification and attribution
- **Key Features**:
  - Automatic citations
  - Source tracking
  - Verification support
- **Use Cases**: Research, legal work, fact-checking

#### **Prompting for Frontend Aesthetics**
- **Path**: `coding/prompting_for_frontend_aesthetics.ipynb`
- **Purpose**: Generate distinctive, polished UI designs
- **Key Features**:
  - Design prompting techniques
  - Aesthetic guidance
  - Anti-generic patterns
- **Use Cases**: UI/UX design, frontend development, design systems

---

### 💡 Skills

#### **Introduction to Claude Skills**
- **Path**: `skills/notebooks/01_skills_introduction.ipynb`
- **Purpose**: Excel, PowerPoint, PDF skills overview
- **Key Features**:
  - Document creation
  - Data analysis
  - Workflow automation
- **Use Cases**: Business automation, reporting, document generation

#### **Claude Skills for Financial Applications**
- **Path**: `skills/notebooks/02_skills_financial_applications.ipynb`
- **Purpose**: Financial dashboards and portfolio analytics
- **Key Features**:
  - Excel automation
  - PowerPoint reporting
  - Financial analysis
- **Use Cases**: Investment analysis, reporting, portfolio management

#### **Building Custom Skills**
- **Path**: `skills/notebooks/03_skills_custom_development.ipynb`
- **Purpose**: Create and deploy custom organizational skills
- **Key Features**:
  - Skill development framework
  - Deployment process
  - Management tools
- **Use Cases**: Enterprise customization, workflow extensions, specialized tools

---

### 🧠 Thinking

#### **Extended Thinking**
- **Path**: `extended_thinking/extended_thinking.ipynb`
- **Purpose**: Transparent step-by-step reasoning
- **Key Features**:
  - Visible thinking process
  - Budget management
  - Complex problem solving
- **Use Cases**: Mathematical reasoning, strategic planning, complex analysis

#### **Extended Thinking with Tool Use**
- **Path**: `extended_thinking/extended_thinking_with_tool_use.ipynb`
- **Purpose**: Transparent reasoning during tool workflows
- **Key Features**:
  - Multi-step transparency
  - Tool integration
  - Reasoning visibility
- **Use Cases**: Complex workflows, debugging, educational applications

---

### 📊 Evals

#### **Building Evals**
- **Path**: `misc/building_evals.ipynb`
- **Purpose**: Measure and improve Claude performance
- **Key Features**:
  - Evaluation framework
  - Metrics definition
  - Quality measurement
- **Use Cases**: Quality assurance, performance optimization, system validation

#### **Generate Test Cases**
- **Path**: `misc/generate_test_cases.ipynb`
- **Purpose**: Synthetic test data for prompt templates
- **Key Features**:
  - Test case generation
  - Template evaluation
  - Coverage improvement
- **Use Cases**: Testing, validation, quality control

#### **Tool Evaluation**
- **Path**: `tool_evaluation/tool_evaluation.ipynb`
- **Purpose**: Independent tool performance evaluation
- **Key Features**:
  - Parallel evaluations
  - Task-based testing
  - Performance metrics
- **Use Cases**: Tool validation, benchmarking, optimization

---

### 📈 Observability

#### **Usage & Cost Admin API**
- **Path**: `observability/usage_cost_api.ipynb`
- **Purpose**: Programmatic usage and cost analysis
- **Key Features**:
  - Admin API integration
  - Usage tracking
  - Cost monitoring
- **Use Cases**: Budget management, usage analytics, cost optimization

---

### 🎯 Fine-Tuning

#### **Finetuning Claude 3 Haiku on Bedrock**
- **Path**: `finetuning/finetuning_on_bedrock.ipynb`
- **Purpose**: Custom task fine-tuning guide
- **Key Features**:
  - Bedrock integration
  - Step-by-step process
  - Custom model creation
- **Use Cases**: Specialized tasks, domain adaptation, performance optimization

---

### 🚀 Claude Agent SDK

#### **00 - The One-Liner Research Agent**
- **Path**: `claude_agent_sdk/00_The_one_liner_research_agent.ipynb`
- **Purpose**: Minimal autonomous research agent
- **Key Features**:
  - SDK fundamentals
  - WebSearch tool
  - Simple configuration
- **Use Cases**: Quick prototyping, research automation, learning SDK

#### **01 - The Chief of Staff Agent**
- **Path**: `claude_agent_sdk/01_The_chief_of_staff_agent.ipynb`
- **Purpose**: Advanced multi-agent orchestration
- **Key Features**:
  - Subagent management
  - Hooks and styles
  - Plan mode capabilities
- **Use Cases**: Complex projects, multi-domain tasks, enterprise automation

#### **02 - The Observability Agent**
- **Path**: `claude_agent_sdk/02_The_observability_agent.ipynb`
- **Purpose**: External system integration
- **Key Features**:
  - MCP server connectivity
  - GitHub integration
  - CI/CD workflows
- **Use Cases**: DevOps, monitoring, system integration

---

## Quick Reference by Category

### By Difficulty Level

**Beginner**
- Getting Started with Vision
- Calculator Tool
- JSON Mode
- Prompt Caching
- Classification with Claude

**Intermediate**
- Retrieval Augmented Generation
- Customer Service Agent
- Basic Workflows
- Building Evals
- Extended Thinking

**Advanced**
- Contextual Retrieval
- Programmatic Tool Calling
- Orchestrator Workers
- Chief of Staff Agent
- Tool Search with Embeddings

### By Use Case

**Document Processing**
- PDF Upload Summarization
- How to Transcribe Documents
- Reading Charts and Graphs
- Crop Tool
- Summarization with Claude

**Data Analysis**
- Text to SQL
- SQL Queries
- Citations
- Building Evals
- Usage & Cost API

**Automation**
- Customer Service Agent
- Building Moderation Filter
- Batch Processing
- Memory & Context Management
- Skills Introduction

**Integration**
- All third_party cookbooks
- Tool Use patterns
- MCP server integration
- Agent SDK tutorials

**AI Research & Development**
- Extended Thinking
- Evaluator Optimizer
- Generate Test Cases
- Metaprompt
- Fine-tuning on Bedrock

---

## Next Steps

1. **Explore by category**: Start with your use case
2. **Check workflows**: See [Innovative Workflows](01_INNOVATIVE_WORKFLOWS.md)
3. **Review best practices**: See category-specific guides
4. **Build your application**: Combine patterns for your needs

For detailed workflow examples combining multiple cookbooks, see the [Innovative Workflows document](01_INNOVATIVE_WORKFLOWS.md).
