# Mutiullah Shaikh - AI Engineer Portfolio

> AI & Software Engineer building reliable LLM, RAG, multi-agent, and production AI systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-2563EB?style=for-the-badge&logo=github)](https://mutsh.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mutishaikh/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/mutsh)

## About Me

I am an AI & Software Engineer with a PhD in Software Engineering and 12+ years of experience across software development, AI engineering, technical delivery, and digital transformation.

I build deployable AI solutions using LLMs, retrieval-augmented generation (RAG), multi-agent systems, Python, APIs, tool integration, and modern AI frameworks. My work focuses on AI reliability, evaluation, observability, security, governance, and measurable business impact.

- Based in Odense, Denmark
- Interested in AI Engineer, Applied AI Engineer, Generative AI Engineer, Agentic AI Engineer, and AI Solutions Architect roles
- Email: [mutishaikh@live.com](mailto:mutishaikh@live.com)
- LinkedIn: [linkedin.com/in/mutishaikh](https://www.linkedin.com/in/mutishaikh/)
- GitHub: [github.com/mutsh](https://github.com/mutsh)

## Featured Projects

### 1. VANTAGE

**Vulnerability Assessment and Testing Automation for Global Enhancements**

A multi-agent cybersecurity system for vulnerability assessment and threat intelligence. It combines specialized agents, orchestration, SIEM data, and observability to support autonomous security operations.

**Tech:** Python, PyTorch, LangChain, LangGraph, SIEM data, agent orchestration

[View project](https://github.com/mutsh/VANTAGE)

### 2. Customer Feedback RAG Chatbot

An LLM-powered CLI assistant that turns 117,968 validated Amazon Electronics feedback records into fast, traceable answers for customer-support and product teams.

**Tech:** Python, LangChain, RAG, embeddings, vector search, AutoML

[View project](https://github.com/mutsh/Customer_Feedback_Agent_RAG)

### 3. CareSense Agentic AI

An automated multi-agent platform for evidence-driven research and information extraction. It combines structured and unstructured data, automated evaluation, AI observability, governance dashboards, and stakeholder reporting.

**Tech:** Python, multi-agent systems, automated evaluation, CI/CD, AI governance

[View project](https://github.com/mutsh/CareSense_Agnetic_AI)

## Technical Skills

| Area | Technologies |
| --- | --- |
| Generative and Agentic AI | LLMs, RAG, multi-agent systems, prompt engineering, context engineering, tool/function calling |
| AI and Machine Learning | Python, PyTorch, TensorFlow, Hugging Face, scikit-learn, NLP, deep learning |
| AI Frameworks | LangChain, LangGraph, LangSmith |
| AI Quality | AI evals, groundedness, faithfulness, hallucination detection, retrieval evaluation |
| Data and APIs | SQL, PostgreSQL, Databricks, ETL/ELT, data pipelines, REST APIs |
| Responsible AI | Explainable AI, AI security, guardrails, HITL, governance, auditability |
| Cloud and MLOps | Azure, AWS, Docker, Kubernetes, CI/CD, monitoring, logging, observability |

## Selected Impact

- Engineered trustworthy AI systems targeting **0.84 AUROC**, **0.78 Macro-F1**, **0.82 Recall@5**, and **under 2.5 seconds P95 latency**.
- Built multi-agent workflows targeting **90%+ task completion** and **93%+ tool-execution accuracy**.
- Standardized evaluation and observability across **5+ agent workflows**.
- Delivered **12+ AI/software PoCs and MVPs** for **6+ stakeholders**.
- Led enterprise software and digital-transformation initiatives across multidisciplinary teams.

## Education

- **PhD, Engineering and Science (Software Engineering)** - University of Southern Denmark, 2023-2026
- **ME, Computer Information Engineering** - Mehran University of Engineering & Technology, 2012-2015
- **BE, Computer Systems Engineering** - Mehran University of Engineering & Technology, 2008-2011

## Certifications

- Build with Claude API - Anthropic
- LLM Course - Hugging Face
- AI Agents & Agentic AI - 365 Data Science
- Data Analysis in Python - University of Copenhagen
- International Blockchain Summer School - IT University of Copenhagen
- Project Management Professional (PMP)
- Certified Information Systems Auditor (CISA)
- Cisco Certified Network Associate (CCNA)

---

# Build and Publish This Portfolio

The simplest route is **GitHub Pages + a Jekyll theme**. It is free and does not require a server.

## Theme Choices

Choose one theme by changing a single line in `_config.yml`:

| Theme | Best for | `_config.yml` value |
| --- | --- | --- |
| Cayman | Modern blue landing page - recommended | `theme: jekyll-theme-cayman` |
| Minimal | Clean and professional | `theme: jekyll-theme-minimal` |
| Midnight | Dark technology look | `theme: jekyll-theme-midnight` |

## Step 1 - Create the GitHub Repository

1. Sign in at [github.com](https://github.com).
2. Click **New repository**.
3. Name it exactly `mutsh.github.io`.
4. Select **Public**.
5. Tick **Add a README file**.
6. Click **Create repository**.

Your website address will be: `https://mutsh.github.io`

## Step 2 - Add the Portfolio Homepage

1. In the new repository, click **Add file > Create new file**.
2. Name the file `index.md`.
3. Copy everything from the top of this document, starting at `# Mutiullah Shaikh`, and stop before `# Build and Publish This Portfolio`.
4. Click **Commit changes**.

## Step 3 - Add a Theme

1. Click **Add file > Create new file** again.
2. Name the file `_config.yml`.
3. Paste:

```yaml
title: Mutiullah Shaikh
description: AI Engineer | LLMs | RAG | Multi-Agent Systems | Responsible AI
theme: jekyll-theme-cayman
show_downloads: false
```

4. Commit the file.

To use a different theme later, replace `jekyll-theme-cayman` with `jekyll-theme-minimal` or `jekyll-theme-midnight`.

## Step 4 - Publish with GitHub Pages

1. Open the repository's **Settings**.
2. In the left menu, click **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Click **Save**.
6. Wait 2-10 minutes, then open `https://mutsh.github.io`.

## Step 5 - Improve the Portfolio

Add these items next:

1. A professional profile photo saved as `assets/profile.jpg`.
2. One screenshot or architecture diagram for each featured project.
3. A downloadable CV named `Mutiullah_Shaikh_CV.pdf`.
4. Short project case studies covering the problem, architecture, evaluation, results, and lessons learned.
5. GitHub repository links with complete documentation and working demos.

To link your CV from `index.md`, add:

```markdown
[Download my CV](./Mutiullah_Shaikh_CV.pdf)
```

## Recommended Repository Structure

```text
mutsh.github.io/
|-- _config.yml
|-- index.md
|-- README.md
|-- Mutiullah_Shaikh_CV.pdf
|-- assets/
|   |-- profile.jpg
|   |-- vantage.png
|   |-- customer-feedback-rag.png
|   `-- caresense.png
`-- projects/
    |-- vantage.md
    |-- customer-feedback-rag.md
    `-- caresense.md
```

## Optional - Use Your Own Domain

After the free GitHub Pages site is working, you can buy a domain such as `mutiullahshaikh.com`. Add it under **Settings > Pages > Custom domain**, then follow your domain provider's DNS instructions.

## Portfolio Quality Checklist

- [ ] Homepage clearly says what role you want
- [ ] Three strongest projects appear near the top
- [ ] Every project explains the problem, architecture, evaluation, and result
- [ ] Project repositories have screenshots and setup instructions
- [ ] Email, LinkedIn, GitHub, and CV links work
- [ ] Website works on both desktop and mobile
- [ ] No spelling mistakes or broken links
- [ ] GitHub Pages deployment is successful

## License

The portfolio content is personal. Code examples may be reused under the MIT License unless a project repository states otherwise.
