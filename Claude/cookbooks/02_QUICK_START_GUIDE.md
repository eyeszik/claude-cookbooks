# Quick Start Guide: Claude Cookbooks

## New to Claude Cookbooks?

Start here! This guide helps you quickly find the right cookbook for your needs and get started in minutes.

## Table of Contents
- [5-Minute Quick Starts](#5-minute-quick-starts)
- [By Role](#by-role)
- [By Industry](#by-industry)
- [By Goal](#by-goal)
- [Common Patterns](#common-patterns)
- [Learning Paths](#learning-paths)

---

## 5-Minute Quick Starts

### "I want to try Claude with images"
**Start**: `multimodal/getting_started_with_vision.ipynb`
1. Load the notebook
2. Add your API key
3. Run all cells
4. Try with your own images

**Time**: 5 minutes | **Difficulty**: ⭐

---

### "I need to build a chatbot"
**Start**: `tool_use/customer_service_agent.ipynb`
1. Define your tools (customer lookup, etc.)
2. Configure the agent
3. Test conversations
4. Deploy

**Time**: 15 minutes | **Difficulty**: ⭐⭐

---

### "I want to process documents at scale"
**Start**: `misc/batch_processing.ipynb`
1. Prepare your document list
2. Submit batch job
3. Monitor progress
4. Collect results

**Time**: 10 minutes | **Difficulty**: ⭐

---

### "I need structured data from text"
**Start**: `tool_use/extracting_structured_json.ipynb`
1. Define your schema
2. Run extraction
3. Validate output
4. Integrate into pipeline

**Time**: 10 minutes | **Difficulty**: ⭐⭐

---

### "I want to build a RAG system"
**Start**: `capabilities/retrieval_augmented_generation/guide.ipynb`
1. Prepare your documents
2. Create embeddings
3. Build retrieval pipeline
4. Test queries

**Time**: 30 minutes | **Difficulty**: ⭐⭐⭐

---

### "I need to analyze SQL data"
**Start**: `capabilities/text_to_sql/guide.ipynb`
1. Provide database schema
2. Test natural language queries
3. Validate SQL generation
4. Deploy

**Time**: 20 minutes | **Difficulty**: ⭐⭐

---

## By Role

### 🎨 **Frontend Developers**
1. **Prompting for Frontend Aesthetics** - `coding/prompting_for_frontend_aesthetics.ipynb`
   - Generate polished UI designs
   - Avoid generic aesthetics
   - **Quick Win**: Better design prompts in 10 minutes

2. **Vision with Tools** - `tool_use/vision_with_tools.ipynb`
   - Extract structured data from UI mockups
   - **Quick Win**: Convert designs to specs

3. **JSON Mode** - `misc/how_to_enable_json_mode.ipynb`
   - Get reliable JSON for components
   - **Quick Win**: Type-safe API responses

**Learning Path**: JSON Mode → Frontend Aesthetics → Vision with Tools (1-2 hours total)

---

### 🔧 **Backend Developers**
1. **Customer Service Agent** - `tool_use/customer_service_agent.ipynb`
   - Build API-connected agents
   - **Quick Win**: Working chatbot in 20 minutes

2. **Text to SQL** - `capabilities/text_to_sql/guide.ipynb`
   - Natural language database queries
   - **Quick Win**: Query interface in 30 minutes

3. **Tool Use with Pydantic** - `tool_use/tool_use_with_pydantic.ipynb`
   - Type-safe tool definitions
   - **Quick Win**: Validated tools in 15 minutes

4. **Batch Processing** - `misc/batch_processing.ipynb`
   - Scale to production
   - **Quick Win**: 50% cost reduction

**Learning Path**: Tool Use with Pydantic → Customer Service Agent → Batch Processing → Text to SQL (2-3 hours)

---

### 📊 **Data Scientists**
1. **RAG Pipeline** - `capabilities/retrieval_augmented_generation/guide.ipynb`
   - Build knowledge bases
   - **Quick Win**: Working RAG in 45 minutes

2. **Contextual Retrieval** - `capabilities/contextual-embeddings/guide.ipynb`
   - 67% accuracy improvement
   - **Quick Win**: Better retrieval immediately

3. **Classification** - `capabilities/classification/guide.ipynb`
   - Build classifiers
   - **Quick Win**: Custom classifier in 30 minutes

4. **Building Evals** - `misc/building_evals.ipynb`
   - Measure model performance
   - **Quick Win**: Evaluation framework in 30 minutes

**Learning Path**: Classification → RAG → Contextual Retrieval → Building Evals (3-4 hours)

---

### 🤖 **AI Engineers**
1. **Basic Workflows** - `patterns/agents/basic_workflows.ipynb`
   - Multi-LLM patterns
   - **Quick Win**: 3 workflow patterns in 20 minutes

2. **Orchestrator Workers** - `patterns/agents/orchestrator_workers.ipynb`
   - Advanced multi-agent
   - **Quick Win**: Coordinated agents in 45 minutes

3. **Extended Thinking with Tools** - `extended_thinking/extended_thinking_with_tool_use.ipynb`
   - Transparent reasoning
   - **Quick Win**: Better problem solving

4. **Chief of Staff Agent** - `claude_agent_sdk/01_The_chief_of_staff_agent.ipynb`
   - Complete agent system
   - **Quick Win**: Production-ready agent framework

**Learning Path**: Basic Workflows → Extended Thinking → Orchestrator Workers → Chief of Staff (4-6 hours)

---

### 💼 **Product Managers**
1. **Generate Test Cases** - `misc/generate_test_cases.ipynb`
   - Create test scenarios
   - **Quick Win**: Comprehensive test suite in 15 minutes

2. **Metaprompt** - `misc/metaprompt.ipynb`
   - Generate requirements
   - **Quick Win**: Better specifications

3. **Building Evals** - `misc/building_evals.ipynb`
   - Define success metrics
   - **Quick Win**: Measurable outcomes

4. **Skills - PowerPoint** - `skills/notebooks/01_skills_introduction.ipynb`
   - Generate presentations
   - **Quick Win**: Auto-generated decks

**Learning Path**: Metaprompt → Generate Test Cases → Building Evals → Skills (2-3 hours)

---

### 📝 **Content Creators**
1. **Prompting for Frontend Aesthetics** - `coding/prompting_for_frontend_aesthetics.ipynb`
   - Better content prompts
   - **Quick Win**: Distinctive content style

2. **Building Moderation Filter** - `misc/building_moderation_filter.ipynb`
   - Content safety
   - **Quick Win**: Brand compliance in 20 minutes

3. **Evaluator Optimizer** - `patterns/agents/evaluator_optimizer.ipynb`
   - Quality improvement loop
   - **Quick Win**: Better content quality

4. **Batch Processing** - `misc/batch_processing.ipynb`
   - Scale content creation
   - **Quick Win**: 10x throughput

**Learning Path**: Prompting Techniques → Evaluator Optimizer → Batch Processing (2 hours)

---

### 🔬 **Researchers**
1. **The One-Liner Research Agent** - `claude_agent_sdk/00_The_one_liner_research_agent.ipynb`
   - Autonomous research
   - **Quick Win**: Research automation in 10 minutes

2. **Citations** - `misc/using_citations.ipynb`
   - Source verification
   - **Quick Win**: Cited answers

3. **Summarization** - `capabilities/summarization/guide.ipynb`
   - Document summarization
   - **Quick Win**: Paper summaries in minutes

4. **Skills - PowerPoint** - `skills/notebooks/01_skills_introduction.ipynb`
   - Research presentations
   - **Quick Win**: Auto-generated slides

**Learning Path**: Research Agent → Summarization → Citations → Skills (2-3 hours)

---

### 🎯 **DevOps Engineers**
1. **The Observability Agent** - `claude_agent_sdk/02_The_observability_agent.ipynb`
   - CI/CD monitoring
   - **Quick Win**: Automated monitoring

2. **Usage & Cost API** - `observability/usage_cost_api.ipynb`
   - Track API usage
   - **Quick Win**: Cost visibility

3. **Extended Thinking with Tools** - `extended_thinking/extended_thinking_with_tool_use.ipynb`
   - Root cause analysis
   - **Quick Win**: Better debugging

4. **Chief of Staff Agent** - `claude_agent_sdk/01_The_chief_of_staff_agent.ipynb`
   - Orchestrate operations
   - **Quick Win**: Automated workflows

**Learning Path**: Observability Agent → Usage & Cost API → Extended Thinking → Chief of Staff (3-4 hours)

---

## By Industry

### 💰 **Financial Services**
**Quick Start Path**:
1. Skills - Financial Applications (30 min)
2. Reading Charts and Graphs (20 min)
3. Text to SQL (30 min)
4. Building Evals (30 min)

**Key Cookbooks**:
- `skills/notebooks/02_skills_financial_applications.ipynb` - Financial dashboards
- `multimodal/reading_charts_graphs_powerpoints.ipynb` - Chart analysis
- `capabilities/text_to_sql/guide.ipynb` - Data queries
- `capabilities/classification/guide.ipynb` - Risk classification
- `misc/using_citations.ipynb` - Audit trails

**First Project**: Automated earnings report analysis
**Time to Value**: 2-3 hours

---

### 🏥 **Healthcare**
**Quick Start Path**:
1. PDF Upload Summarization (20 min)
2. How to Transcribe Documents (30 min)
3. Building Moderation Filter (20 min)
4. Extracting Structured JSON (20 min)

**Key Cookbooks**:
- `misc/pdf_upload_summarization.ipynb` - Medical records
- `multimodal/how_to_transcribe_text.ipynb` - Form processing
- `misc/building_moderation_filter.ipynb` - HIPAA compliance
- `tool_use/extracting_structured_json.ipynb` - Structured data
- `misc/using_citations.ipynb` - Source tracking

**First Project**: Patient record summarization
**Time to Value**: 2 hours

---

### ⚖️ **Legal**
**Quick Start Path**:
1. Summarization (45 min)
2. Classification (30 min)
3. Citations (20 min)
4. Extracting Structured JSON (20 min)

**Key Cookbooks**:
- `capabilities/summarization/guide.ipynb` - Contract summaries
- `capabilities/classification/guide.ipynb` - Document routing
- `misc/using_citations.ipynb` - Source verification
- `tool_use/extracting_structured_json.ipynb` - Clause extraction
- `extended_thinking/extended_thinking.ipynb` - Legal reasoning

**First Project**: Contract review automation
**Time to Value**: 2-3 hours

---

### 🛒 **E-commerce**
**Quick Start Path**:
1. Vision with Tools (20 min)
2. Batch Processing (15 min)
3. Classification (30 min)
4. Customer Service Agent (30 min)

**Key Cookbooks**:
- `tool_use/vision_with_tools.ipynb` - Product images
- `misc/batch_processing.ipynb` - Scale catalog
- `capabilities/classification/guide.ipynb` - Product categorization
- `tool_use/customer_service_agent.ipynb` - Support automation
- `third_party/MongoDB/rag_using_mongodb.ipynb` - Product search

**First Project**: Product description generation
**Time to Value**: 2 hours

---

### 📚 **Education**
**Quick Start Path**:
1. Extended Thinking (20 min)
2. Generate Test Cases (20 min)
3. Memory & Context Management (30 min)
4. Building Evals (30 min)

**Key Cookbooks**:
- `extended_thinking/extended_thinking.ipynb` - Step-by-step teaching
- `misc/generate_test_cases.ipynb` - Quiz generation
- `tool_use/memory_cookbook.ipynb` - Student progress
- `misc/building_evals.ipynb` - Assessment
- `patterns/agents/evaluator_optimizer.ipynb` - Feedback loops

**First Project**: Adaptive quiz system
**Time to Value**: 2-3 hours

---

### 📰 **Media & Publishing**
**Quick Start Path**:
1. Summarization (30 min)
2. Building Moderation Filter (20 min)
3. Batch Processing (15 min)
4. Evaluator Optimizer (30 min)

**Key Cookbooks**:
- `misc/read_web_pages_with_haiku.ipynb` - Content curation
- `capabilities/summarization/guide.ipynb` - Article summaries
- `misc/building_moderation_filter.ipynb` - Content safety
- `misc/batch_processing.ipynb` - Scale production
- `patterns/agents/evaluator_optimizer.ipynb` - Quality control

**First Project**: Automated news summarization
**Time to Value**: 2 hours

---

## By Goal

### 🎯 "I want to save costs"
**Priority Cookbooks**:
1. **Batch Processing** - `misc/batch_processing.ipynb`
   - 50% cost reduction
   - **Impact**: High | **Effort**: Low

2. **Prompt Caching** - `misc/prompt_caching.ipynb`
   - 90% cost savings on cached content
   - **Impact**: High | **Effort**: Low

3. **Using Sub-Agents** - `multimodal/using_sub_agents.ipynb`
   - Use Haiku for simple tasks
   - **Impact**: Medium | **Effort**: Medium

4. **Automatic Context Compaction** - `tool_use/automatic-context-compaction.ipynb`
   - Reduce token usage
   - **Impact**: Medium | **Effort**: Medium

**Quick Win Path**: Prompt Caching → Batch Processing (30 minutes, immediate savings)

---

### ⚡ "I want to improve performance"
**Priority Cookbooks**:
1. **Contextual Retrieval** - `capabilities/contextual-embeddings/guide.ipynb`
   - 67% accuracy improvement
   - **Impact**: Very High | **Effort**: Medium

2. **Evaluator Optimizer** - `patterns/agents/evaluator_optimizer.ipynb`
   - Quality feedback loop
   - **Impact**: High | **Effort**: Medium

3. **Extended Thinking** - `extended_thinking/extended_thinking.ipynb`
   - Better reasoning
   - **Impact**: High | **Effort**: Low

4. **Building Evals** - `misc/building_evals.ipynb`
   - Measure and improve
   - **Impact**: High | **Effort**: Medium

**Quick Win Path**: Extended Thinking → Building Evals → Evaluator Optimizer (2 hours)

---

### 📈 "I want to scale up"
**Priority Cookbooks**:
1. **Batch Processing** - `misc/batch_processing.ipynb`
   - Handle 1000s of requests
   - **Impact**: Very High | **Effort**: Low

2. **Tool Search with Embeddings** - `tool_use/tool_search_with_embeddings.ipynb`
   - Scale to 1000s of tools
   - **Impact**: High | **Effort**: Medium

3. **Automatic Context Compaction** - `tool_use/automatic-context-compaction.ipynb`
   - Handle long conversations
   - **Impact**: Medium | **Effort**: Medium

4. **RAG using Pinecone** - `third_party/Pinecone/rag_using_pinecone.ipynb`
   - Production vector DB
   - **Impact**: High | **Effort**: High

**Quick Win Path**: Batch Processing → Tool Search → RAG (4-6 hours)

---

### 🔒 "I need compliance/safety"
**Priority Cookbooks**:
1. **Building Moderation Filter** - `misc/building_moderation_filter.ipynb`
   - Content safety
   - **Impact**: Very High | **Effort**: Low

2. **Citations** - `misc/using_citations.ipynb`
   - Source verification
   - **Impact**: High | **Effort**: Low

3. **Classification** - `capabilities/classification/guide.ipynb`
   - Risk detection
   - **Impact**: High | **Effort**: Medium

4. **Extended Thinking** - `extended_thinking/extended_thinking.ipynb`
   - Explainable AI
   - **Impact**: Medium | **Effort**: Low

**Quick Win Path**: Moderation Filter → Citations (40 minutes)

---

### 🤖 "I want to build agents"
**Priority Cookbooks**:
1. **The One-Liner Research Agent** - `claude_agent_sdk/00_The_one_liner_research_agent.ipynb`
   - Start simple
   - **Impact**: Medium | **Effort**: Very Low

2. **Basic Workflows** - `patterns/agents/basic_workflows.ipynb`
   - Learn patterns
   - **Impact**: High | **Effort**: Low

3. **Orchestrator Workers** - `patterns/agents/orchestrator_workers.ipynb`
   - Multi-agent systems
   - **Impact**: High | **Effort**: Medium

4. **Chief of Staff Agent** - `claude_agent_sdk/01_The_chief_of_staff_agent.ipynb`
   - Advanced agents
   - **Impact**: Very High | **Effort**: High

**Quick Win Path**: One-Liner Agent → Basic Workflows → Orchestrator → Chief of Staff (4-6 hours)

---

## Common Patterns

### Pattern: Extract → Process → Validate

**Use Cases**: Document processing, data extraction, form filling

**Cookbooks**:
1. Vision with Tools OR Extracting Structured JSON
2. Classification OR Text to SQL
3. Evaluator Optimizer

**Time**: 1-2 hours
**Example**: Invoice processing pipeline

---

### Pattern: Research → Analyze → Report

**Use Cases**: Business intelligence, market research, competitive analysis

**Cookbooks**:
1. The One-Liner Research Agent
2. Extended Thinking OR Orchestrator Workers
3. Summarization + Citations
4. Skills (PowerPoint/Excel)

**Time**: 2-3 hours
**Example**: Market research automation

---

### Pattern: Classify → Route → Respond

**Use Cases**: Customer service, content moderation, ticket routing

**Cookbooks**:
1. Classification
2. Customer Service Agent OR Tool Choice
3. Memory & Context Management

**Time**: 1-2 hours
**Example**: Intelligent chatbot

---

### Pattern: Index → Retrieve → Generate

**Use Cases**: Knowledge bases, Q&A systems, RAG applications

**Cookbooks**:
1. Contextual Retrieval OR RAG Pipeline
2. Prompt Caching
3. Citations

**Time**: 2-4 hours
**Example**: Enterprise knowledge base

---

### Pattern: Generate → Evaluate → Refine

**Use Cases**: Content creation, code generation, decision making

**Cookbooks**:
1. Extended Thinking OR Metaprompt
2. Evaluator Optimizer
3. Building Evals

**Time**: 1-2 hours
**Example**: High-quality content pipeline

---

## Learning Paths

### 🌱 **Beginner Path** (4-6 hours)
**Goal**: Understand Claude capabilities and build first application

1. **Getting Started with Vision** (30 min)
   - Understand multi-modal

2. **JSON Mode** (20 min)
   - Structured outputs

3. **Calculator Tool** (30 min)
   - Tool use basics

4. **Customer Service Agent** (45 min)
   - Build first agent

5. **Prompt Caching** (30 min)
   - Cost optimization

6. **Building Evals** (45 min)
   - Measure performance

**First Project**: Build a simple customer service chatbot
**Skills Gained**: Basics of tool use, structured outputs, evaluation

---

### 🌿 **Intermediate Path** (8-12 hours)
**Prerequisites**: Completed beginner path

1. **Classification** (1 hour)
   - Advanced categorization

2. **RAG Pipeline** (2 hours)
   - Build knowledge base

3. **Contextual Retrieval** (1.5 hours)
   - Improve accuracy

4. **Basic Workflows** (1 hour)
   - Multi-agent patterns

5. **Extended Thinking with Tools** (1.5 hours)
   - Complex reasoning

6. **Batch Processing** (1 hour)
   - Scale to production

7. **Evaluator Optimizer** (1.5 hours)
   - Quality loops

**Project**: RAG-powered Q&A system with quality assurance
**Skills Gained**: RAG, multi-agent, production readiness

---

### 🌳 **Advanced Path** (12-20 hours)
**Prerequisites**: Completed intermediate path

1. **Tool Search with Embeddings** (2 hours)
   - Scale tools

2. **Programmatic Tool Calling** (2 hours)
   - Advanced tool use

3. **Orchestrator Workers** (2 hours)
   - Complex multi-agent

4. **The Chief of Staff Agent** (3 hours)
   - Complete agent system

5. **The Observability Agent** (2 hours)
   - System integration

6. **Skills - Custom Development** (3 hours)
   - Build custom capabilities

7. **Automatic Context Compaction** (2 hours)
   - Long-running agents

**Project**: Enterprise-grade multi-agent system with observability
**Skills Gained**: Production systems, complex orchestration, custom development

---

### 🎯 **Specialist Paths**

#### **RAG Specialist** (10-15 hours)
1. Basic RAG → Contextual Retrieval → Multi-Document Agents
2. Router Query Engine → SubQuestion Query Engine
3. MongoDB/Pinecone integration
4. Building Evals for RAG

**Outcome**: Expert RAG systems

---

#### **Agent Specialist** (12-18 hours)
1. Basic Workflows → Evaluator Optimizer → Orchestrator Workers
2. Extended Thinking → Tool patterns
3. Research Agent → Chief of Staff → Observability
4. Custom agent development

**Outcome**: Advanced multi-agent systems

---

#### **Vision Specialist** (8-12 hours)
1. Getting Started → Best Practices → Transcription
2. Charts & Graphs → Crop Tool → Vision with Tools
3. Multi-Modal workflows
4. Batch processing for images

**Outcome**: Production vision systems

---

#### **Production Engineer** (10-15 hours)
1. Batch Processing → Prompt Caching → Context Compaction
2. Building Evals → Tool Evaluation
3. Usage & Cost API → Observability Agent
4. Integration patterns (Pinecone, MongoDB, etc.)

**Outcome**: Production-ready deployments

---

## Quick Reference: Time & Difficulty

### ⏱️ Under 30 Minutes
- Getting Started with Vision ⭐
- JSON Mode ⭐
- Prompt Caching ⭐
- Building Moderation Filter ⭐⭐
- Citations ⭐
- Batch Processing ⭐
- Metaprompt ⭐
- Generate Test Cases ⭐⭐

### ⏱️ 30-60 Minutes
- Calculator Tool ⭐
- Customer Service Agent ⭐⭐
- Classification ⭐⭐
- Text to SQL ⭐⭐
- Extracting Structured JSON ⭐⭐
- Tool Use with Pydantic ⭐⭐
- Extended Thinking ⭐⭐
- Basic Workflows ⭐⭐

### ⏱️ 1-2 Hours
- RAG Pipeline ⭐⭐⭐
- Contextual Retrieval ⭐⭐⭐
- Summarization ⭐⭐
- Orchestrator Workers ⭐⭐⭐
- Memory & Context Management ⭐⭐⭐
- Tool Search with Embeddings ⭐⭐⭐

### ⏱️ 2+ Hours
- Chief of Staff Agent ⭐⭐⭐⭐
- Programmatic Tool Calling ⭐⭐⭐⭐
- Skills - Custom Development ⭐⭐⭐⭐
- Multi-Document Agents ⭐⭐⭐
- Observability Agent ⭐⭐⭐

---

## Getting Help

### Documentation
- **Full catalog**: [Comprehensive Overview](00_COMPREHENSIVE_OVERVIEW.md)
- **Workflows**: [Innovative Workflows](01_INNOVATIVE_WORKFLOWS.md)
- **Categories**: [Category Deep Dive](03_CATEGORY_DEEP_DIVE.md)

### Common Issues
1. **API Key**: Copy `.env.example` to `.env` and add `ANTHROPIC_API_KEY`
2. **Dependencies**: Run `uv sync --all-extras`
3. **Notebook errors**: Restart kernel and run all cells
4. **Rate limits**: Use batch processing or prompt caching

### Next Steps
1. Pick a cookbook from your role/industry
2. Follow the quick start
3. Measure results
4. Combine patterns for complex workflows
5. Scale to production

**Ready to build? Start with your first cookbook now!** 🚀
