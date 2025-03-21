
# Multi-Agent Blog Writing System - Crew AI

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 🚀 Overview

![multi agent blog writer.png](<multi agent blog writer.png>)

The **Multi-Agent Blog Writing System (Crew AI)** is an innovative project that utilizes cutting-edge technologies to automate the process of creating well-researched, human-like blogs. This system is designed to bridge the gap between AI automation and human creativity by incorporating the latest advancements in **Agentic AI**.

This project features a **multi-agent architecture** that autonomously plans, writes, and edits blog posts, ensuring they are accurate, engaging, and up-to-date with the latest trends.


https://github.com/user-attachments/assets/9475289e-5e7a-4cc3-99c9-6ca01b7fb11a

---

## 📁 Project Structure

```
multi-agent/
│
├── client/
│   └── bloggpt/          # Next.js frontend for blog generation
│       ├── pages/        # Next.js pages
│       ├── components/   # Reusable React components
│       ├── actions/      # API calls to the FastAPI backend
│       ├── tailwind.config.js
│       ├── package.json
│       └── ...
│
│── crewai.ipynb      # Jupyter Notebook with FastAPI server and AI logic
│── requirements.txt  # Python dependencies
│── ...
```

---

## 🌟 Features

- **Planner Agent**: Structures and strategizes blog content based on the input query.
- **Writer Agent**: Generates the blog content using the **Gemini 2.0-Flash-EXP** LLM.
- **Editor Agent**: Refines the content for clarity, engagement, and accuracy.
- **Integration with Serper Web Search**: Fetches the latest information and trends.
- **FastAPI Backend**: Handles blog generation requests.
- **Next.js Frontend**: Provides a sleek user interface for input and blog display.
- **End-to-End Automation**: Delivers a complete, polished blog with references.



