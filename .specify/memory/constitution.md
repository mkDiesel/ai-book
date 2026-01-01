<!--
    Sync Impact Report:
    - Version change: 0.0.0 -> 1.0.0
    - List of modified principles:
        - [PRINCIPLE_1_NAME] -> I. Specification-Driven Development
        - [PRINCIPLE_2_NAME] -> II. Source-Verified Technical Accuracy
        - [PRINCIPLE_3_NAME] -> III. Clarity for Developers
        - [PRINCIPLE_4_NAME] -> IV. Content-Grounded AI
    - Added sections: Key Standards, Constraints
    - Removed sections: PRINCIPLE_5, PRINCIPLE_6
    - Templates requiring updates:
        - ✅ .specify/templates/plan-template.md
        - ✅ .specify/templates/spec-template.md
        - ✅ .specify/templates/tasks-template.md
-->
# Unified AI/spec-Driven Book with Embedded RAG Chatbot Constitution

## Core Principles

### I. Specification-Driven Development
The project is developed using Spec-Kit Plus to ensure a reproducible setup and deployment. All development work is guided by specifications.

### II. Source-Verified Technical Accuracy
All technical content must be accurate and verifiable. Claude Code will be used for structured content generation to maintain high quality.

### III. Clarity for Developers
Explanations and documentation should be clear, concise, and aimed at a developer audience.

### IV. Content-Grounded AI
The RAG chatbot must not hallucinate. Its answers must be strictly grounded in the content of the book. When an answer cannot be found, it must provide a clear fallback response.

## Key Standards
- Book written in Markdown/MDX using Docusaurus and deployed on github pages
- Claude Code for structured content generation
- Spec-Kit Plus defines chapters and constraints
- RAG stack: OpenAI Agents/ChatKit, FastAPI, Qdrant Cloud (Free), Neon Postgres
- Chatbot supports full-book and selected-text Q&A

## Constraints
- Deploy to GitHub Pages
- RAG responses limited to indexed book content
- Clear fallback when answer not found
- Clean, modular, open-source–compliant code

## Governance
This Constitution is the single source of truth for project principles and standards. All development artifacts, including specifications, plans, and code, must adhere to it. Amendments require a documented proposal, review, and approval process.

**Version**: 1.0.0 | **Ratified**: 2025-12-28 | **Last Amended**: 2025-12-28