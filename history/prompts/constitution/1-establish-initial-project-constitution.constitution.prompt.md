---
id: 1
title: Establish Initial Project Constitution
stage: constitution
date: 2025-12-28
surface: agent
model: {{MODEL}}
feature: none
branch: master
user: {{USER}}
command: /sp.constitution
labels: [project-setup, constitution]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
  - .specify/templates/plan-template.md
tests:
  - "none"
---

## Prompt

/sp.constitution

Project: Unified AI/spec-Driven Book with Embedded RAG Chatbot

Objective:
Create and deploy a technical book using Spec-Kit Plus and Claude Code with Docusaurus on GitHub Pages, including an embedded RAG chatbot that answers questions strictly from the book content and user-selected text.

Core Principles:
- Spec-driven using spec-kit plus and reproducible setup and deployment
- Source-verified technical accuracy
- Clear explanations for developers
- No hallucinations; content-grounded AI only
 

Key Standards:
- Book written in Markdown/MDX using Docusaurus and deployed on github pages
- Claude Code for structured content generation
- Spec-Kit Plus defines chapters and constraints
- RAG stack: OpenAI Agents/ChatKit, FastAPI, Qdrant Cloud (Free), Neon Postgres
- Chatbot supports full-book and selected-text Q&A

Constraints:
- Deploy to GitHub Pages
- RAG responses limited to indexed book content
- Clear fallback when answer not found
- Clean, modular, open-source–compliant code

Success Criteria:
- Successful build and deployment
- Spec-compliant chapters
- Accurate, grounded chatbot responses
- Reproducible setup and documentation

## Response snapshot

Created the initial project constitution in `.specify/memory/constitution.md` and updated the plan template in `.specify/templates/plan-template.md` to reflect the new principles.

## Outcome

- ✅ Impact: {{OUTCOME_IMPACT}}
- 🧪 Tests: {{TESTS_SUMMARY}}
- 📁 Files: {{FILES_SUMMARY}}
- 🔁 Next prompts: {{NEXT_PROMPTS}}
- 🧠 Reflection: {{REFLECTION_NOTE}}

## Evaluation notes (flywheel)

- Failure modes observed: {{FAILURE_MODES}}
- Graders run and results (PASS/FAIL): {{GRADER_RESULTS}}
- Prompt variant (if applicable): {{PROMPT_VARIANT_ID}}
- Next experiment (smallest change to try): {{NEXT_EXPERIMENT}}
