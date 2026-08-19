<h1 align="center">LLMOps Applied Program</h1>

<p align="center">Project-based, portfolio-first learning</p>

<div align="center">

<a href="https://ds500.paiml.com"><img src="https://img.shields.io/badge/Platform-Pragmatic_AI_Labs-blue" /></a>
<a href="https://ds500.paiml.com/mailing"><img src="https://img.shields.io/badge/Newsletter-Join-blue" /></a>
<a href="https://discord.gg/JJEcK7uzFS"><img src="https://img.shields.io/discord/973306113946681374" /></a>

</div>

<p align="center">
  <a href="https://ds500.paiml.com"><img src="resources/applied-program.png" alt="Banner" /></a>
</p>


An 8-week, project-based, portfolio-first program on operationalizing Large
Language Models (LLMOps). Build a real LLM application, ship it publicly, and
walk away with a portfolio piece, not a grade.


<details>
  <summary><b>Table of Contents</b></summary>
  <br>

* [How this program works](#how-this-program-works)
* [Prerequisites](#prerequisites)
* [Week 1: Generative AI Concepts + Dev Environment Setup](#week-1-generative-ai-concepts--dev-environment-setup)
* [Week 2: Interacting with Large Language Models](#week-2-interacting-with-large-language-models)
* [Week 3: Local Large Language Models](#week-3-local-large-language-models)
* [Week 4: Applied Solutions + Extensibility](#week-4-applied-solutions--extensibility)
* [Week 5: Retrieval Augmented Generation](#week-5-retrieval-augmented-generation)
* [Week 6: Python Web Frameworks for APIs](#week-6-python-web-frameworks-for-apis)
* [Week 7: DevOps Principles + Deploying ML APIs](#week-7-devops-principles--deploying-ml-apis)
* [Week 8: LLM Platforms + Ship & Finalize](#week-8-llm-platforms--ship--finalize)
* [The Project](#the-project)
* [Community](#community)
* [PROJECT.md](./PROJECT.md) — full project guidance

</details>

[The Project](./PROJECT.md) · [Self-Assessment Checklist](./SELF_ASSESSMENT.md)

## How this program works

There's no grading, no enrollment gate, and no required login. Everything you
need to complete the program is in this repository.

There are two ways to run through it:

* **Rolling (self-paced):** Start whenever you want. No meetings, no
  cohort — you work through the 8 weeks on your own schedule and
  self-assess your project against the [checklist](./SELF_ASSESSMENT.md).
* **Cohort:** Runs alongside a shared start date with a dedicated Discord
  channel and an end-of-run call where participants demo their projects to
  each other (peer feedback, not grading).

Each week lists a plain-language objective, supporting resources, and a demo
video prompt. The video prompt is worth doing even outside a cohort — it's
the habit that turns a week of work into a LinkedIn post and a portfolio
entry.

> [!IMPORTANT]
> You are not required to watch or read every resource listed. Nothing here
> is graded. Use the content as support for your project, not as a
> checklist to complete for its own sake.

> [!NOTE]
> **Diversity Statement:** We share a commitment to diversity and equity,
> removing barriers to learning so that everyone can participate fully.
> This program is meant to be useful to people with a wide range of
> backgrounds, identities, and learning styles, whether you found it through
> a cohort or on your own on GitHub.

### Prerequisites

Basic Linux and programming skills. You can complete all project work in
either Python or Rust — you don't need both.

**Linux**

If you need to shore up basic Linux skills: [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)

**Python**

* [Python Essentials for MLOps – Week 1: Introduction to Python](https://ds500.paiml.com/course/o184n/1) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Python Essentials for MLOps – Week 2: Python Functions and Classes](https://ds500.paiml.com/course/o184n/2) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)

**Rust**

* [Rust Fundamentals](https://ds500.paiml.com/course/g6u1k) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)

#### Additional support resources

* [LLMOps with Azure](https://ds500.paiml.com/course/lxulo) · [Coursera](https://www.coursera.org/learn/llmops-azure)
* [Cloud Machine Learning Engineering and MLOps](https://ds500.paiml.com/course/f5sj1)
* [Rust Data Engineering](https://ds500.paiml.com/course/9dyuw) · [Coursera](https://www.coursera.org/learn/data-engineering-rust)
* [Cloud Computing Foundations](https://ds500.paiml.com/course/4ycpb)
* [Python Essentials for MLOps](https://ds500.paiml.com/course/o184n) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)

## 8-Week Syllabus

### Week 1: Generative AI Concepts + Dev Environment Setup

* [Introduction to Generative AI](https://ds500.paiml.com/course/0bbb5/1/2/3) · [Coursera](https://www.coursera.org/learn/intro-gen-ai)
* [Public Speaking](https://github.com/microsoft/workshop-library/tree/main/short/public-speaking)
* [Developing Effective Technical Communication](https://www.coursera.org/learn/cloud-computing-foundations-duke/home/week/2)
* [Exploring Cloud Onboarding](https://ds500.paiml.com/course/4ycpb/3/1/2)
* [Python Development Environments](https://ds500.paiml.com/course/qzyhh/1/2/2)
* [Pytest Master Class](https://ds500.paiml.com/course/o184n/3/1/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Python Essentials for MLOps – Week 5: Applied Python for MLOps](https://ds500.paiml.com/course/o184n/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* Rust: [Setting up your Rust Development environment](https://ds500.paiml.com/course/g6u1k/5/1/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)

**Tasks:**

1. Choose the problem your project will solve, and who it's for (see
   [PROJECT.md](./PROJECT.md))
2. Choose your programming stack — Python or Rust
3. Set up your dev environment and initialize the project repository

**Weekly demo video prompt:** Discuss your plan for your individual project — what you're building and how you'll pace it over the next 8 weeks — and describe your programming language choice, including its advantages and potential pitfalls. Use the [Public Speaking](https://github.com/microsoft/workshop-library/tree/main/short/public-speaking) guidelines to deliver a great demo.

### Week 2: Interacting with Large Language Models

* [Interacting with models](https://ds500.paiml.com/course/0bbb5/1/4/5) · [Coursera](https://www.coursera.org/learn/intro-gen-ai)
* [Building robust Generative AI systems](https://ds500.paiml.com/course/0bbb5/1/3/4) · [Coursera](https://www.coursera.org/learn/intro-gen-ai)
* [Introduction to MLOps Walkthrough](https://ds500.paiml.com/course/f5sj1/3/1/1)
* [MLOps Foundations: Chapter 2 Walkthrough of Practical MLOps](https://ds500.paiml.com/course/f5sj1/3/1/3)
* [Practical MLOps, Chapter 1: Introduction to MLOps](https://ds500.paiml.com/course/f5sj1/3/1/1)
* [Practical MLOps, Chapter 2: MLOps Foundations](https://ds500.paiml.com/course/f5sj1/3/1/2)

**Tasks:**

1. Decide how you'll interact with the SLM/LLM (direct API calls, an SDK, a
   local server's HTTP endpoint, etc.)
2. Experiment with prompts against a model and note the failure modes your
   application will need to handle (bad output, timeouts, hallucination)
3. Sketch the input/output contract your application expects from the model

**Weekly demo video prompt:** Explain some challenges your application will face working with LLM output, and what you'll do to mitigate them.

### Week 3: Local Large Language Models

* [Beginning Llamafile for Local Large Language Models (LLMs)](https://ds500.paiml.com/course/2pzqq/2/1/2) · [Coursera](https://www.coursera.org/learn/llamafile-local-llm)
* [Getting Started with Open Source Ecosystem](https://ds500.paiml.com/course/zr1li/1) · [Coursera](https://www.coursera.org/learn/open-source-llmops-solutions)
* [Foundations of Local Large Language Models](https://ds500.paiml.com/course/vm5ox/1) · [Coursera](https://www.coursera.org/learn/local-large-language-models)

**Tasks:**

1. Evaluate the local LLMs/SLMs available to you (Llamafile, Ollama,
   llama.cpp, etc.) against your problem
2. Choose the model and serving tool for your project
3. Get it running locally and confirm you can call it programmatically from
   your application's stack

**Weekly demo video prompt:** Describe your evaluation of the local LLMs/SLMs available with Llamafile and which one fits your project best.

### Week 4: Applied Solutions + Extensibility

* [Local LLMOps](https://ds500.paiml.com/course/zr1li) · [Coursera](https://www.coursera.org/learn/open-source-llmops-solutions)
* [AI Pair Programming from CodeWhisperer to Prompt Engineering](https://ds500.paiml.com/course/qzyhh/2/2/2)
* [Using Local LLMs from Llamafile to Whisper.cpp](https://ds500.paiml.com/course/zr1li/2/3/2) · [Coursera](https://www.coursera.org/learn/open-source-llmops-solutions)
* [Open Source Platforms for MLOps – Week 2: Introduction to Hugging Face](https://ds500.paiml.com/course/w3qih/2/1/2) · [Coursera](https://www.coursera.org/learn/mlops-mlflow-huggingface-duke)
* [Open Source Platforms for MLOps – Week 3: Deploying Hugging Face](https://ds500.paiml.com/course/w3qih/4/1/4) · [Coursera](https://www.coursera.org/learn/mlops-mlflow-huggingface-duke)
* [Open Source Platforms for MLOps – Week 4: Applied Hugging Face](https://ds500.paiml.com/course/w3qih/2/2/2) · [Coursera](https://www.coursera.org/learn/mlops-mlflow-huggingface-duke)
* [Extending with Functions and Plugins](https://ds500.paiml.com/course/lxulo/3/1/2) · [Coursera](https://www.coursera.org/learn/llmops-azure)
* [Applications of LLMs](https://ds500.paiml.com/course/0bbb5/3/1/3) · [Coursera](https://www.coursera.org/learn/intro-gen-ai)
* [MLOps Platforms: Amazon SageMaker and Azure ML – Week 1](https://ds500.paiml.com/course/y7ji0/1) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)

**Tasks:**

1. Build the core application logic around the model — input handling,
   prompt construction, output parsing, error handling
2. Identify what plugins or functions would extend your application, and
   pick one to prototype
3. Sketch an architectural overview of your application

**Weekly demo video prompt:** Walk through the architectural overview of your application and its challenges, and explain what plugins or functions would extend it — and what would make that harder in a production environment.

### Week 5: Retrieval Augmented Generation

* [Introduction to Retrieval Augmented Generation (RAG)](https://ds500.paiml.com/course/0bbb5/3/2/3) · [Coursera](https://www.coursera.org/learn/introduction-to-rag)
* [Emerging Topics in Machine Learning](https://ds500.paiml.com/course/f5sj1/3)

**Tasks:**

1. Decide whether RAG fits your project — not every project needs it
2. If it does, implement a basic retrieval pipeline over your document set
3. If it doesn't, document why, so the decision shows up in your project's
   history and demo

**Weekly demo video prompt:** How would adding RAG to your application change the experience for an end user? Why would you (or wouldn't you) use RAG here?

### Week 6: Python Web Frameworks for APIs

* [Introduction to FastAPI Framework](https://ds500.paiml.com/course/o184n/5/3/5) · [Coursera](https://www.coursera.org/learn/introduction-to-fastapi-framework)
* [Introduction to Flask Framework](https://ds500.paiml.com/course/o184n/5/3/3) · [Coursera](https://www.coursera.org/learn/introduction-to-flask-framework)
* [Applied Python for MLOps](https://ds500.paiml.com/course/o184n/5) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Cloud Virtualization, Containers and APIs](https://ds500.paiml.com/course/2qt9g/2/2/4)

**Tasks:**

1. Choose a web framework (FastAPI, Flask, or a Rust equivalent) if your
   interface needs one — skip this if your interface is a CLI
2. Wire the framework into your existing application logic
3. Expose your application's endpoints and confirm they work end to end

**Weekly demo video prompt:** What are the benefits of the framework you chose, and how will you wire it into your application?

### Week 7: DevOps Principles + Deploying ML APIs

* [Responsible Generative AI](https://ds500.paiml.com/course/4saal) · [Coursera](https://www.coursera.org/learn/ai-security-and-governance-on-aws)
* [Applying DevOps Principles](https://ds500.paiml.com/course/4ycpb/5)
* [MLOps Platforms: Amazon SageMaker and Azure ML – Week 2](https://ds500.paiml.com/course/y7ji0/2) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [MLOps Platforms: Amazon SageMaker and Azure ML – Week 3](https://ds500.paiml.com/course/y7ji0/3) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [Introduction to GitHub Actions](https://ds500.paiml.com/course/ldfsk/6/1/5) · [Coursera](https://www.coursera.org/learn/introduction-to-github-actions)
* [Building an End-to-End LLM application in Azure](https://ds500.paiml.com/course/ap1hj/1) · [Coursera](https://www.coursera.org/learn/azure-llm-large-language-models)
* [Operations](https://ds500.paiml.com/course/2qt9g/4)

**Tasks:**

1. Containerize the application, without baking the model into the image
2. Set up GitHub Actions CI to build the container image on push
3. Apply and document basic DevOps and responsible-AI practices for your
   project

**Weekly demo video prompt:** How are you applying DevOps and responsible AI principles — and automation — to your application? What difficulties came up building the automation, and how will it benefit the project going forward?

### Week 8: LLM Platforms + Ship & Finalize

* [Introduction to LLMOps with Azure](https://ds500.paiml.com/course/lxulo/1/3/5) · [Coursera](https://www.coursera.org/learn/llmops-azure)
* [mlflow-project-best-practices](https://github.com/noahgift/mlflow-project-best-practices)
* [MLOps Platforms From Zero: Databricks, MLFlow/MLRun/SKLearn](https://ds500.paiml.com/course/lzjzv)
* [Azure Databricks, Pandas, and Opendatasets](https://ds500.paiml.com/course/13cq4) · [Coursera](https://www.coursera.org/learn/data-engineering-with-delta-lake-on-databricks)
* [MLOps Platforms: Amazon SageMaker and Azure ML – Week 4](https://ds500.paiml.com/course/y7ji0/4) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [MLOps Platforms: Amazon SageMaker and Azure ML – Week 5](https://ds500.paiml.com/course/y7ji0/5) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)

**Tasks:**

1. Evaluate what a cloud LLM platform would change about your application,
   as a point of comparison to your local/self-deployed setup
2. Run your project against the [self-assessment
   checklist](./SELF_ASSESSMENT.md)
3. Publish the repository publicly and write a short portfolio/LinkedIn post
   linking to it

Finish the project: publish the repository, run it against the
[self-assessment checklist](./SELF_ASSESSMENT.md), and write a short
portfolio/LinkedIn post pointing at the repo. Rolling learners get a closing
email when they hit this week; cohort learners present on the end-of-run
call instead of (or in addition to) posting.

**Weekly demo video prompt:** How would adding a cloud LLM platform change what your application can do, and what's a drawback of relying on one? Wrap with a short demo of the finished project.

## The Project

The whole program is built around a single project you start in Week 1 and
ship in Week 8: an application that solves a real problem using a local or
self-deployed LLM/SLM. See [PROJECT.md](./PROJECT.md) for what that means
and how to scope it, and the [self-assessment
checklist](./SELF_ASSESSMENT.md) for what "done" looks like.

> [!IMPORTANT]
> **Do not build a model yourself.** Reuse an existing LLM or SLM. Use
> [Mozilla Llamafile](https://github.com/Mozilla-Ocho/llamafile) as a
> reference for running one locally, or another local serving tool (Ollama,
> llama.cpp, etc.) — details in [PROJECT.md](./PROJECT.md).

The primary two resources for building an LLM solution on a local API:

1. [Beginning Llamafile for Local Large Language Models (LLMs)](https://ds500.paiml.com/course/2pzqq/2/1/2) · [Coursera](https://www.coursera.org/learn/llamafile-local-llm)
2. [Getting Started with Open Source Ecosystem](https://ds500.paiml.com/course/zr1li/1) · [Coursera](https://www.coursera.org/learn/open-source-llmops-solutions)

#### Machine Learning References

* [Hugging Face](https://huggingface.co/)
* [TensorFlow Hub](https://www.tensorflow.org/hub)
* [Classify text with BERT](https://www.tensorflow.org/text/tutorials/classify_text_with_bert)

#### AutoML References

* [AutoML with CreateML](https://ds500.paiml.com/course/f5sj1/2/1/5)
* [AutoML and KaizenML](https://ds500.paiml.com/course/f5sj1/2/1/4)

#### Python References

* [Python MLOps Cookbook](https://github.com/noahgift/Python-MLOps-Cookbook)
* [databricks-zero-to-mlops](https://github.com/noahgift/databricks-zero-to-mlops)
* [Python Fire](https://ds500.paiml.com/course/9uu8k/3/1/10) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Refactoring a Python script into a library called by Python Click CLI](https://ds500.paiml.com/course/9uu8k/1/2/10) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Container Continuous Delivery](https://ds500.paiml.com/course/1uigy/2/1/3)
* [Functions to Containerized Microservice Continuous Delivery to AWS App Runner with Fast API](https://ds500.paiml.com/course/fu7p5/1/3/5) · [Coursera](https://www.coursera.org/learn/devops-dataops-mlops-duke)

### Referenced Media and Resources

* [mlflow-project-best-practices](https://github.com/noahgift/mlflow-project-best-practices)
* [databricks-zero-to-mlops](https://github.com/noahgift/databricks-zero-to-mlops)
* [Python MLOps Cookbook](https://github.com/noahgift/Python-MLOps-Cookbook)
* [Edge Computer Vision](https://github.com/noahgift/edge-computer-vision)
* [GitHub Codespaces](https://github.com/features/codespaces)
* [AWS Academy](https://www.awsacademy.com/SiteLogin)
* [Azure for Students](https://azure.microsoft.com/en-us/developer/students/#build)
* [Google Qwiklabs](https://www.qwiklabs.com/)
* [Practical MLOps](https://ds500.paiml.com/course/f5sj1)
* [Pragmatic AI](https://ds500.paiml.com/course/4ycpb)

<details>
<summary><b>Optional supplementary readings & media</b></summary>

* [AWS Bootcamp](https://github.com/noahgift/aws-bootcamp)
* [Python for DevOps](https://ds500.paiml.com/course/o184n) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Practical MLOps](https://ds500.paiml.com/course/f5sj1)
* [Cloud Computing for Data Analysis](https://paiml.com/docs/home/books/cloud-computing-for-data/)
* [Pragmatic AI: An Introduction to Cloud-Based Machine Learning](https://ds500.paiml.com/course/4ycpb)
* [AWS Training & Certification](https://www.aws.training/)
* [AWS Educate](https://www.awseducate.com/educator/s/pathways)
* [AWS Academy](https://aws.amazon.com/training/awsacademy/)
* [Google Qwiklabs – Hands-On Cloud Training](https://www.qwiklabs.com/)
* [Microsoft Learn](https://docs.microsoft.com/en-us/learn/)
* [Applied Computer Vision with Python Lectures](https://ds500.paiml.com/course/f5sj1/2/1/3)
* [Learn Python in One Hour](https://ds500.paiml.com/course/o184n/1) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Cloud Computing with Python](https://ds500.paiml.com/course/4ycpb)
* [Python for Data Science with Colab and Pandas in One Hour](https://ds500.paiml.com/course/o184n/4/1/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [GCP Cloud Functions](https://ds500.paiml.com/course/4ycpb/3/3/9)
* [Azure AutoML](https://ds500.paiml.com/course/n1h1s/1/3/5)

**AWS**

* [AWS Certified Cloud Practitioner Video Course](https://ds500.paiml.com/course/kymo3/1/1/5)
* [Cloud Computing for Data](https://ds500.paiml.com/course/4ycpb)
* [AWS in One](https://ds500.paiml.com/course/0mcoe)
* [AWS Certified Machine Learning – Specialty video course](https://ds500.paiml.com/course/y7ji0/4/3/9) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [AWS Machine Learning](https://ds500.paiml.com/course/y7ji0) · [Coursera](https://www.coursera.org/learn/mlops-aws-azure-duke)
* [AWS Solutions Architect](https://ds500.paiml.com/course/0mcoe/3/2/1)

**GCP**

* [Building AI Applications with GCP](https://ds500.paiml.com/course/mbjn5)
* [Build GCP Cloud Functions](https://ds500.paiml.com/course/4ycpb/3/3/9)

**Python**

* [Data Science, Pandas, and Colab](https://ds500.paiml.com/course/o184n/4/1/3) · [Coursera](https://www.coursera.org/learn/python-mlops-duke)
* [Python and DevOps](https://ds500.paiml.com/course/fu7p5) · [Coursera](https://www.coursera.org/learn/devops-dataops-mlops-duke)
* [Python Command-line Tools](https://ds500.paiml.com/course/9uu8k) · [Coursera](https://www.coursera.org/learn/python-rust-linux)

**Linux and Systems Engineering**

* [Docker containers](https://ds500.paiml.com/course/2qt9g/2/2/4)
* [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)

</details>

## Community

Join the shared PAIML Discord to ask questions, share progress, and post
your weekly demos. _(Discord invite link goes here.)_ If you're in a cohort,
you'll also get invited to a dedicated channel for your run, alongside the
shared server.
