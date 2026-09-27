# Ramesh Murala

**AI / Machine Learning Engineer · Python APIs · Retrieval · ML Systems**

I build services around machine learning and language models, with a focus on validation, retrieval quality, failure handling, and cloud deployment. My background spans backend engineering, applied ML, and AWS infrastructure.

This GitHub collects independent projects and reproducible experiments. Each repository separates implemented behavior from deployment work and states what its evaluation does—and does not—measure.

[Portfolio](https://ramesh-portfolio-steel.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/venkatasrisairameshmurala/) · [Email](mailto:venkatasrisairameshmurala@gmail.com)

## Selected engineering projects

| Project | Problem and implementation | Evidence to inspect |
|---|---|---|
| [AgentShield Lab](https://github.com/Ramesh-Murala/Agent-Shield-Lab) | Python scanner and FastAPI service for prompt-injection signals in untrusted agent inputs; normalize Unicode, highlight evidence, and withhold flagged text through an integration gate | [Explore Python scan examples](https://agent-shield-lab.rameshmurala10.chatgpt.site/), local Python API, CI, reproducible 56-case evaluation with reported misses and false alarms |
| [Structured Output Agent](https://github.com/Ramesh-Murala/Structured-Output-Agent) | Make LLM responses usable by typed APIs: Pydantic validation, corrective retries, a shared deadline, and metadata-only failure logs | [Try live demo](https://structured-output-agent-demo.rameshmurala10.chatgpt.site/), API/failure-path tests, CI, scripted fault-injection evaluation |
| [RAG Agent with Citation Validation](https://github.com/Ramesh-Murala/RAG-Agent-with-Citation) | Check retrieved-source attribution and quoted evidence; abstain on missing context and retry invalid citations | Recall@3/MRR@3 fixture, citation-integrity tests, documented semantic limitations |
| [Healthcare MLOps Simulation](https://github.com/Ramesh-Murala/healthcare-mlops-pipeline) | Connect synthetic data generation, model comparison, MLflow tracking, FastAPI serving, and batch scoring | Reproducible training, synthetic evaluation, API tests, container checks |

## How I approach AI engineering

- Define the API contract and failure behavior before adding a model.
- Compare against a simple baseline and keep evaluation inputs reproducible.
- Separate schema correctness, retrieval relevance, and factual accuracy.
- Make unavailable dependencies and exhausted retries visible to callers.
- Document design trade-offs and the work required before deployment.

## Technical focus

**Application engineering:** Python, SQL, FastAPI, Pydantic, automated testing, Docker, GitHub Actions.

**AI and ML:** retrieval-augmented generation, structured output, NLP, scikit-learn, evaluation, MLflow.

**Cloud experience:** AWS inference services and data infrastructure, including SageMaker, ECS, Lambda, S3, and CloudWatch. The public projects above are local reference implementations; their READMEs describe their deployment boundaries.

## Additional work

[ML application prototypes](https://github.com/Ramesh-Murala/ml-saas-portfolio) explore API/frontend integration with explicitly documented mocks and baselines. They are supporting examples, separate from the selected projects above.

I’m interested in AI engineering and ML platform roles where reliable backend systems and measurable model behavior matter.
