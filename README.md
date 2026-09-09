# AI and LLM Engineering Course

An eight-week, project-driven learning journey covering Generative AI, Large Language Models, Frontier APIs, open-source models, Retrieval-Augmented Generation, fine-tuning, agents, and production deployment.

The course progresses from foundational concepts to building and deploying a commercial, agent-enabled, fine-tuned LLM product with a polished user interface.

> [!IMPORTANT]
> This repository is designed for practical learning. Each week combines core concepts, guided experiments, and a business-focused project.

## Course Overview

| Item | Details |
|---|---|
| Duration | 8 weeks |
| Focus | Generative AI and LLM Engineering |
| Learning Style | Theory, experimentation, and project-based development |
| Final Outcome | A productionized, agentized, fine-tuned LLM application |
| Key Areas | Transformers, Frontier Models, APIs, Hugging Face, RAG, fine-tuning, QLoRA, agents, and deployment |

## Learning Outcomes

By completing this course, you will be able to:

- Explain the fundamentals of Transformers and Large Language Models.
- Experiment with leading Frontier Models and their APIs.
- Build multimodal AI applications that work with text, images, and audio.
- Use open-source models through Hugging Face.
- Select an appropriate LLM for a specific business requirement.
- Build Retrieval-Augmented Generation solutions using embeddings and vector databases.
- Fine-tune Frontier and open-source models for specialized tasks.
- Apply advanced fine-tuning techniques such as QLoRA.
- Add tools and agent capabilities to LLM applications.
- Deploy an AI product with a polished user interface.

## Course Structure

> [!NOTE]
> Every week includes a practical outcome that contributes to the skills required for the final production project.

### Week 1: Foundations and First Projects

- Dive into the fundamentals of Transformers.
- Experiment with six leading Frontier Models.
- Build your first business Gen AI product that scrapes the web, makes decisions, and creates formatted sales brochures.

**Project milestone:** Business brochure generator.

---

### Week 2: Frontier APIs and Customer Service Chatbots

- Explore Frontier APIs and interact with three leading models.
- Develop a customer service chatbot with a sharp UI that can interact with text, images, audio, and utilize tools or agents.

**Project milestone:** Multimodal customer service chatbot.

---

### Week 3: Embracing Open-Source Models

- Discover the world of Open-Source models using HuggingFace.
- Tackle 10 common Gen AI use cases, from translation to image generation.
- Build a product to generate meeting minutes and action items from recordings.

**Project milestone:** Meeting minutes and action-item generator.

---

### Week 4: LLM Selection and Code Generation

- Understand the differences between LLMs and how to select the best one for your business tasks.
- Use LLMs to generate code and build a product that translates code from Python to C++, achieving performance improvements of over 60,000 times.

**Project milestone:** AI-assisted Python-to-C++ code translator and performance comparison.

> [!CAUTION]
> Performance improvements depend on the workload, generated implementation, compiler configuration, hardware, and benchmark methodology. Validate all generated code and measure results in a controlled environment.

---

### Week 5: Retrieval-Augmented Generation (RAG)

- Master RAG to improve the accuracy of your solutions.
- Become proficient with vector embeddings and explore vectors in popular open-source vector datastores.
- Build a full business solution similar to real products on the market today.

**Project milestone:** Business-focused RAG application.

---

### Week 6: Transitioning to Training

- Move from inference to training.
- Fine-tune a Frontier model to solve a real business problem.
- Build your own specialized model, marking a significant milestone in your AI journey.

**Project milestone:** Fine-tuned specialized business model.

---

### Week 7: Advanced Training Techniques

- Dive into advanced training techniques like QLoRA fine-tuning.
- Train an open-source model to outperform Frontier models for specific tasks.
- Tackle challenging projects that push your skills to the next level.

**Project milestone:** QLoRA-tuned open-source model for a targeted task.

---

### Week 8: Deployment and Finalization

- Deploy your commercial product to production with a polished UI.
- Enhance capabilities using Agents.
- Deliver your first productionized, agentized, fine-tuned LLM model.
- Celebrate your mastery of AI and LLM engineering, ready for a new phase in your career.

**Final milestone:** Productionized, agent-enabled, fine-tuned LLM product.

## Projects

The repository can contain the following major projects:

1. **Sales Brochure Generator**
   - Collects permitted public web content.
   - Extracts relevant business information.
   - Uses an LLM to make content decisions.
   - Produces a formatted sales brochure.

2. **Multimodal Customer Service Chatbot**
   - Supports text, images, and audio.
   - Uses tools or agents to complete approved tasks.
   - Includes a user-friendly chat interface.

3. **Meeting Intelligence Assistant**
   - Processes meeting recordings.
   - Produces structured meeting minutes.
   - Identifies decisions, owners, and action items.

4. **AI Code Translator**
   - Translates selected Python workloads to C++.
   - Validates functional equivalence.
   - Benchmarks execution performance.

5. **Business RAG Solution**
   - Ingests approved business documents.
   - Creates embeddings and stores vectors.
   - Retrieves relevant context for grounded answers.
   - Returns answers with source references where possible.

6. **Specialized Fine-Tuned Model**
   - Uses a curated task-specific dataset.
   - Applies supervised fine-tuning or QLoRA.
   - Compares the tuned model against a baseline.

7. **Production AI Product**
   - Combines RAG, model routing, agents, and a polished UI.
   - Includes security, evaluation, monitoring, and deployment controls.

## Suggested Repository Structure

```text
AI-Engineer/
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
├── requirements.txt
├── pyproject.toml
├── docs/
│   ├── architecture/
│   ├── learning-notes/
│   ├── security/
│   └── deployment/
├── week-01-foundations/
│   ├── notebooks/
│   ├── src/
│   └── README.md
├── week-02-frontier-apis/
│   ├── chatbot/
│   └── README.md
├── week-03-open-source-models/
│   ├── use-cases/
│   ├── meeting-assistant/
│   └── README.md
├── week-04-llm-selection-code-generation/
│   ├── benchmarks/
│   ├── code-translator/
│   └── README.md
├── week-05-rag/
│   ├── ingestion/
│   ├── retrieval/
│   ├── evaluation/
│   └── README.md
├── week-06-fine-tuning/
│   ├── data/
│   ├── training/
│   └── README.md
├── week-07-advanced-training/
│   ├── qlora/
│   ├── evaluation/
│   └── README.md
├── week-08-deployment/
│   ├── app/
│   ├── agents/
│   ├── infrastructure/
│   └── README.md
├── shared/
│   ├── config/
│   ├── models/
│   ├── prompts/
│   ├── security/
│   └── utils/
└── tests/
    ├── unit/
    ├── integration/
    ├── evaluation/
    └── security/
```

## Suggested Technology Stack

Choose technologies according to the project requirements, approved services, cost limits, and deployment environment.

### Core Development

- Python
- Jupyter Notebook or JupyterLab
- Git and GitHub
- Visual Studio Code
- Virtual environments using `venv`, Conda, or another approved environment manager

### AI and LLM Development

- Frontier model APIs
- Hugging Face Transformers
- Hugging Face Datasets
- Sentence Transformers or provider-supported embeddings
- PyTorch
- Parameter-efficient fine-tuning libraries

### RAG and Data

- Document loaders and text splitters
- Embedding models
- An approved vector database
- Metadata filtering and access control
- Retrieval and answer-quality evaluation

### Application and Deployment

- A Python API framework
- A web-based user interface
- Containerization
- Automated testing and CI/CD
- Logging, monitoring, tracing, and cost tracking

> [!TIP]
> Keep model providers, vector stores, and deployment services configurable. Avoid tightly coupling the application to a single provider unless the business requirement demands it.

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd ai-llm-engineering-course
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Linux or macOS:

```bash
source .venv/bin/activate
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Copy the example environment file:

```bash
cp .env.example .env
```

Add only the credentials and configuration needed for the module you are running.

```dotenv
MODEL_PROVIDER_API_KEY=replace_with_your_key
MODEL_NAME=replace_with_your_model
EMBEDDING_MODEL=replace_with_your_embedding_model
VECTOR_STORE_URL=replace_with_your_vector_store_url
```

> [!WARNING]
> Never commit `.env` files, API keys, access tokens, customer data, production data, or proprietary documents to the repository.

### 5. Start with Week 1

```bash
cd week-01-foundations
```

Follow the module-level `README.md` to install any additional dependencies and run the project.

## Weekly Workflow

For each week:

1. Review the learning objectives.
2. Study the core concepts.
3. Run the guided examples.
4. Complete the weekly experiments.
5. Build the assigned project milestone.
6. Add automated tests.
7. Evaluate quality, latency, safety, and cost.
8. Document observations and limitations.
9. Commit the completed work using a descriptive commit message.

## Evaluation Framework

Do not evaluate an LLM application only by whether a response appears correct. Measure it systematically.

### Quality

- Task completion
- Factual correctness
- Relevance
- Groundedness
- Retrieval precision and recall
- Code correctness
- Output format compliance

### Operational Performance

- End-to-end latency
- Token consumption
- API and infrastructure cost
- Throughput
- Failure rate
- Retry rate

### Safety and Security

- Prompt-injection resistance
- Sensitive-data exposure
- Authorization enforcement
- Unsafe tool calls
- Insecure generated code
- Dependency and secret scanning

### User Experience

- Clarity
- Accessibility
- Error handling
- Responsiveness
- User feedback
- Human escalation paths

## Security and Responsible AI

All projects in this repository should follow secure and responsible AI practices.

- Use only authorized data sources.
- Apply least-privilege access to models, tools, files, and external systems.
- Separate development, testing, and production environments.
- Treat retrieved documents and web content as untrusted input.
- Defend against prompt injection and indirect prompt injection.
- Validate and sanitize model-generated content before execution or publication.
- Require human approval for sensitive or high-impact actions.
- Redact secrets and personal or confidential information from logs.
- Encrypt sensitive data in transit and at rest.
- Record auditable traces for model calls and tool actions.
- Define retention and deletion policies for prompts, responses, and uploaded files.
- Evaluate models for accuracy, safety, bias, latency, and cost before deployment.

## Progress Tracker

- [ ] Week 1: Foundations and First Projects
- [ ] Week 2: Frontier APIs and Customer Service Chatbots
- [ ] Week 3: Embracing Open-Source Models
- [ ] Week 4: LLM Selection and Code Generation
- [ ] Week 5: Retrieval-Augmented Generation (RAG)
- [ ] Week 6: Transitioning to Training
- [ ] Week 7: Advanced Training Techniques
- [ ] Week 8: Deployment and Finalization
- [ ] Final product demonstration
- [ ] Security review completed
- [ ] Documentation completed
- [ ] Production readiness review completed

## Definition of Done

The final project should include:

- A clearly documented business problem and target users.
- A working, polished user interface.
- A documented model-selection decision.
- A secure RAG pipeline where relevant.
- A task-specific fine-tuned model where justified.
- Agent or tool capabilities with explicit permissions.
- Automated unit and integration tests.
- LLM quality and safety evaluations.
- Monitoring for quality, latency, failures, and cost.
- Secure secrets and configuration management.
- Deployment and rollback instructions.
- Known limitations and recommended human-review points.

## Contributing

Contributions are welcome.

1. Create a feature branch.
2. Make a focused change.
3. Add or update tests and documentation.
4. Run all relevant checks locally.
5. Open a pull request describing the purpose, implementation, and validation results.

Please do not include credentials, private datasets, copyrighted datasets without permission, or confidential business information in a contribution.

## License

Add the license selected for your repository in the `LICENSE` file. Ensure that all datasets, model weights, libraries, and external services used by the projects have compatible licenses and usage terms.

## Acknowledgements

This repository follows an eight-week practical learning path focused on developing real-world Generative AI and LLM engineering capabilities through progressively advanced projects.

---

**Start with the foundations, build every week, evaluate continuously, and finish with a secure production-ready AI product.**
