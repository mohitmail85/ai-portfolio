<div align="center">

# 👋 Mohit Gautam — AI Portfolio

**Applied AI engineer building and evaluating LLM systems — RAG pipelines, multi-agent frameworks, and full-stack AI applications.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohitmail85)
[![Email](https://img.shields.io/badge/Email-mohitmail85%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohitmail85@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-mohitmail85-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohitmail85)

![Projects](https://img.shields.io/badge/projects-22%2B-blue?style=flat-square)
![Focus](https://img.shields.io/badge/focus-LLMs%20%7C%20RAG%20%7C%20Agents-6f42c1?style=flat-square)

</div>

---

### About this portfolio

A living index of AI/ML projects — spanning production-style RAG pipelines,
multi-agent systems, rigorous cross-model evaluations, and full-stack
applications. Every project below is a self-contained repo; this page is
the map. Jump to a section:

**[⭐ Featured](#-featured-project) · [Full-Stack AI](#-full-stack-ai-applications) · [RAG & Evaluation](#-rag--retrieval-evaluation) · [Agents](#-ai-agents) · [Cloud & Serverless](#%EF%B8%8F-cloud--serverless-ai) · [Fundamentals](#-fundamentals--learning) · [Systems & More](#%EF%B8%8F-full-stack-system-design--more) · [Tech Stack](#-tech-stack)**

---

## ⭐ Featured project

<table>
<tr>
<td width="70%">

### [insurance-policy-rag-chunking-evaluation](https://github.com/mohitmail85/insurance-policy-rag-chunking-evaluation)

A controlled, reproducible evaluation of RAG chunking strategies for
insurance policy documents — run end-to-end on **two independent LLM
backends (Gemini + Claude)** to rule out single-model bias. Goes beyond a
typical RAG demo with a custom abstention-accuracy metric, a
retrieval-depth (k) ablation, and a documented, corrected measurement
artifact in RAGAS itself — write-up included as an accompanying paper.

**Key finding:** small, fixed-size chunking consistently beats both large
fixed-size and semantic chunking on retrieval precision/recall and
false-refusal rate, on both LLM backends.

</td>
<td width="30%" align="center">

<a href="https://github.com/mohitmail85/insurance-policy-rag-chunking-evaluation">
<img src="https://raw.githubusercontent.com/mohitmail85/insurance-policy-rag-chunking-evaluation/main/paper/figures/combined_ragas_metrics_by_provider.png" width="100%" alt="RAGAS metrics by chunking strategy" />
</a>

</td>
</tr>
</table>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-6f42c1?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square)

---

## 🧠 Full-Stack AI Applications

| Project | Description | Tech Stack |
|---|---|---|
| [research-paper-generator-rag](https://github.com/mohitmail85/research-paper-generator-rag) | RAG-based research paper generator — upload PDFs, build vector index, generate grounded reports with evidence tracking | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| [financial-advisor-ai](https://github.com/mohitmail85/financial-advisor-ai) | Indian stock market investment advisor with multi-agent analysis | ![CrewAI](https://img.shields.io/badge/CrewAI-FF6F61?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) |
| [ai-resume-screener](https://github.com/mohitmail85/ai-resume-screener) | Resume screening app — evaluates resumes against job descriptions with scoring | ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |
| [ai-text-summarizer](https://github.com/mohitmail85/ai-text-summarizer) | Text summarization tool — paste text, get concise summaries | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |

## 🔍 RAG & Retrieval Evaluation

| Project | Description | Tech Stack |
|---|---|---|
| [insurance-policy-rag-chunking-evaluation](https://github.com/mohitmail85/insurance-policy-rag-chunking-evaluation) | Cross-model (Gemini + Claude) evaluation of chunking strategies for RAG, with an abstention-accuracy metric and a corrected RAGAS measurement artifact | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![RAGAS](https://img.shields.io/badge/RAGAS-6f42c1?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square) |

## 🤖 AI Agents

| Project | Description | Tech Stack |
|---|---|---|
| [ai-dev-agent](https://github.com/mohitmail85/ai-dev-agent) | Autonomous AI engineering assistant — reads codebases, writes code, runs checks, raises PRs | ![Claude Agent SDK](https://img.shields.io/badge/Claude%20Agent%20SDK-D97757?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [ai-movie-agent](https://github.com/mohitmail85/ai-movie-agent) | Movie recommendation agent with genre-based matching | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

## ☁️ Cloud & Serverless AI

| Project | Description | Tech Stack |
|---|---|---|
| [openai-lambda-alexa-skill](https://github.com/mohitmail85/openai-lambda-alexa-skill) | Voice-activated AI assistant — OpenAI on AWS Lambda with Alexa | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![Alexa](https://img.shields.io/badge/Alexa%20Skills-00CAFF?style=flat-square&logo=amazonalexa&logoColor=white) |

## 📚 Fundamentals & Learning

| Project | Description | Tech Stack |
|---|---|---|
| [ai-ml-fundamentals](https://github.com/mohitmail85/ai-ml-fundamentals) | Foundational scripts — LLM basics, RAG, ReAct agents, multi-agent pipelines | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![CrewAI](https://img.shields.io/badge/CrewAI-FF6F61?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |
| [prompt-engineering-guide](https://github.com/mohitmail85/prompt-engineering-guide) | 10 prompt engineering techniques with hands-on examples | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![Together AI](https://img.shields.io/badge/Together%20AI-000000?style=flat-square) ![Llama 3.3](https://img.shields.io/badge/Llama%203.3-0467DF?style=flat-square&logo=meta&logoColor=white) |
| [ai-learning-notebooks](https://github.com/mohitmail85/ai-learning-notebooks) | Jupyter notebooks — GANs, multimodal AI, LangChain, LangGraph, RAG, CrewAI | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |

## 🛠️ Full-Stack, System Design & More

| Project | Description | Tech Stack |
|---|---|---|
| [netflix-lite](https://github.com/mohitmail85/netflix-lite) | Netflix-style streaming UI with micro-frontend architecture | ![React](https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| [stripe-payment-gateway-lambda](https://github.com/mohitmail85/stripe-payment-gateway-lambda) | Stripe payment gateway on AWS Lambda | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white) |
| [springboot-product-catalog-api](https://github.com/mohitmail85/springboot-product-catalog-api) | Product catalog REST API with CRUD operations | ![Java](https://img.shields.io/badge/Java%2017-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) |
| [nextjs-ssr-isr-rendering-demo](https://github.com/mohitmail85/nextjs-ssr-isr-rendering-demo) | Next.js rendering strategies demo (SSR, ISR, SSG) | ![Next.js](https://img.shields.io/badge/Next.js%2015-black?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| [nodejs-npm-package-guide](https://github.com/mohitmail85/nodejs-npm-package-guide) | Guide to creating and publishing npm packages | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white) |
| [react-demo-storybook](https://github.com/mohitmail85/react-demo-storybook) | React component library with Storybook | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white) ![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white) |
| [react-pro-application](https://github.com/mohitmail85/react-pro-application) | React starter with Redux Toolkit | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) |
| [lld](https://github.com/mohitmail85/lld) | Low-Level Design patterns in Java | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) |
| [dsa-algorithms-java](https://github.com/mohitmail85/dsa-algorithms-java) | DSA problem solutions in Java | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) |
| [ProblemSolving](https://github.com/mohitmail85/ProblemSolving) | DSA solutions in C# | ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![.NET 6](https://img.shields.io/badge/.NET%206-512BD4?style=flat-square&logo=dotnet&logoColor=white) |
| [socket-programming](https://github.com/mohitmail85/socket-programming) | Real-time chat application | ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |

---

## 🧰 Tech Stack

**LLM Providers**
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20GPT--4o-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic%20Claude-D97757?style=flat-square)
![Together AI](https://img.shields.io/badge/Together%20AI%20(Llama%203.3)-000000?style=flat-square)

**Frameworks**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6F61?style=flat-square)
![Claude Agent SDK](https://img.shields.io/badge/Claude%20Agent%20SDK-D97757?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-6f42c1?style=flat-square)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & Storage**
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20SAM-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Alexa Skills Kit](https://img.shields.io/badge/Alexa%20Skills%20Kit-00CAFF?style=flat-square&logo=amazonalexa&logoColor=white)

---

<div align="center">

### 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=mohitmail85&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohitmail85&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165"/>

---

⭐ **If something here is useful to you, consider starring the repo.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohitmail85)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohitmail85@gmail.com)

</div>
