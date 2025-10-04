Assignment 2: Ground the Domain - From Naive RAG to Production Patterns

Ground the Domain - From Naive RAG to Production Patterns
1. Assignment Overview
Objective: Develop practical expertise in Retrieval-Augmented Generation (RAG) systems by implementing naive RAG and two production-ready enhancements, then evaluating performance using industry-standard metrics to understand real-world RAG deployment challenges.

Core Learning Goals: By completing this assignment, you will demonstrate proficiency in RAG pipeline architecture, advanced retrieval techniques, systematic evaluation using RAGAs/ARES frameworks, and evidence-based optimization of retrieval-augmented systems for production deployment.

 
2. Resource Access and Equity
Supported Platforms (Free/Accessible)
Large Language Models: - Claude.ai (free tier) - ChatGPT-3.5 (free tier) - Google Gemini (free tier) - Llama 3.1/3.2 via Ollama (local installation) - Mistral 7B via Ollama or Hugging Face - Qwen 2.5 via Ollama or Hugging Face Transformers - Flan-T5 (various sizes) via Hugging Face Transformers
Embedding Models: - sentence-transformers (all-MiniLM-L6-v2, all-mpnet-base-v2) - Hugging Face sentence embeddings (free tier) - text-embedding-ada-002 (if using free OpenAI credits)
Vector Databases: - FAISS (Facebook AI Similarity Search - completely free) - Milvus Lite (local, lightweight version) - Chroma (open-source vector database) - Weaviate (free tier for small datasets)
Computational Platforms: - Google Colab (free tier with GPU access) - Kaggle Notebooks (free GPU hours) - Local development (CPU-based implementations supported)
Alternative Platforms (Optional)
If you have personal subscriptions or free credits, you may use: - ChatGPT-4o, GPT-4, or GPT-4 Turbo (OpenAI) - Claude 3.5 Sonnet or Claude Pro (Anthropic) - Gemini Pro or Gemini Advanced (Google) - Commercial APIs: OpenAI, Anthropic, Cohere, or Perplexity Pro - Cloud Computing: AWS, Google Cloud, or Azure free/student credits - Premium Vector Databases: Pinecone, Qdrant Cloud, or Weaviate Cloud

Equity Policy
No Required Purchases: Students are NOT required to obtain premium versions of LLMs, cloud services, or computational resources
No Penalties: Students will NOT be penalized for using open-source, open-weight, or free-tier models instead of premium alternatives
Equal Assessment: All submissions will be evaluated based on methodology, analysis quality, and technical understanding—not on the sophistication of paid tools used
Dataset Access
Primary Dataset: RAG Mini WikipediaLinks to an external site.
 

3. Progressive Assignment Structure
Step 1: Domain Documents (Days 1-2)
Deliverable: Dataset Setup and Exploration Report (300 words)

Requirements:

1. Dataset Access: Download and explore the RAG Mini Wikipedia datasetLinks to an external site.

2. Data Understanding: Document dataset structure, sample entries, and data quality observations

3. Infrastructure Planning: Set up development environment and verify access to chosen platforms

Step 2: Build Naive RAG (Days 3-5)
Deliverable: Functional RAG Pipeline + Documentation (500 words + code)

Technical Requirements:

1. Embed with sentence-transformers: Use “all-MiniLM-L6-v2” as recommended

2. Store embeddings in vector DB: Use Milvus Lite or FAISS as recommended
3. Search and generate: Implement retrieval and response generation

Code Organization: - Modular implementation with clear documentation - Error handling and logging - Configuration files for easy parameter adjustment

Step 3: Evaluation Phase I (Days 6-8)
Deliverable: Initial Evaluation Results (400 words + results)

Requirements:

1. Generate answers: Pass top-1 retrieved document to prompt

2. Prompting strategies: Use different approaches (CoT, Persona Prompting, Instruction Prompt, etc.)

3. Calculate metrics: F1-score and Exact Match using HuggingFace Squad metric 4.

4. Document best strategy: Note which prompting strategy performed best with hypothesis

Step 4: Experimentation (Days 9-11)
Deliverable: Parameter Comparison Analysis (500 words + results table)

Experimental Requirements:

1. Embedding sizes: Generate results using at least 2 different embedding sizes (e.g., 256, 384, 512)

2. Retrieval variations: Experiment with top 3/5/10 retrieved documents (at least 2 different passage selection strategies beyond top-1)

3. Repeat evaluation: Apply Step 3 evaluation methodology to all parameter combinations

4. Documentation: Submit results as markdown/PDF document in GitHub repository

Step 5: Add Two Advanced RAG Features (Days 12-13)
Deliverable: Enhanced RAG Implementation (400 words + code)

Enhancement Options (from Merwane Merabet list): - Query rewriting - Reranking
- Metadata filtering - Multi-vector retrieval - Confidence scoring - Context window optimization - Grounded citations

Implementation Requirements: - Choose any two enhancements from the list above - Implement both features and integrate with existing pipeline - Rerun test queries on enhanced system

Step 6: Advanced Evaluation with RAGAs or ARES (Days 14-15)
Deliverable: Automated Evaluation Report (500 words + metrics)

Evaluation Requirements: - Use either RAGAs or ARES to assess naive and enhanced RAG pipelines - Report on at least the following metrics: - Faithfulness - Context precision/recall
- Answer helpfulness or relevance - Compare performance between naive and enhanced systems

Step 7: Synthesis and Reflection (Days 16-17)
Deliverable: Final Summary Report (1000-1250 words)

Report Structure: - Description of naive system with all required details - Experimentation results from Steps 3 and 4 - Rationale for chosen enhancements
- Results from RAGAs/ARES evaluation - Key lessons, limitations, and potential for further improvement

Additional Requirements: - Professional formatting appropriate for technical audience - Evidence-based conclusions with supporting data - AI usage documentation as per course policy

 

4. Enhanced Academic Integrity and AI Collaboration Framework
Comprehensive Usage Documentation
Required Logging (consistent with Assignment 1): - Tool Inventory: All GenAI tools, models, APIs, and libraries used - Usage Log: Specific purposes, input queries, and output utilization - Code Generation: Any AI-assisted code with clear attribution - Content Creation: AI involvement in documentation, analysis, or reporting

Permitted AI Assistance
Acceptable Uses: - Code debugging and optimization suggestions - Technical documentation assistance - Literature review and reference formatting - Performance analysis and interpretation guidance

Required Attribution Format:

## AI Usage Log
- **Tool**: [Name and Version]
- **Purpose**: [Specific task]
- **Input**: [Query or prompt provided]
- **Output Usage**: [How AI response was incorporated]
- **Verification**: [How accuracy was confirmed]

Prohibited Practices
Using AI to implement core RAG components without understanding
Submitting AI-generated analysis as original insights
Using AI to interpret evaluation results without independent verification
Undocumented collaboration with AI systems
Academic Integrity Verification
Required Evidence: - Personal contribution statements for each major component - Decision rationale documentation showing independent reasoning - Technical troubleshooting logs demonstrating hands-on problem solving - Original analysis connecting results to broader RAG concepts
