# Assignment Assistant Agent

An AI-powered agent that automates university assignment workflows by ingesting assignment PDFs, creating stepwise plans, scaffolding code and documentation, running tests, and generating deliverables.

## Project Details

**Name:** [Your Name]  
**University:** [Your University]  
**Department:** [Your Department]  

*Please replace the placeholders above with your actual information before submission.*

## Architecture

The Assignment Assistant Agent is built with a multi-agent architecture featuring a Planner that creates structured task plans and an Executor that runs tasks with proper tooling. The system includes document ingestion with RAG capabilities, a modern web interface, and background task processing for scalable execution.

## Tech Stack

- **Backend:** FastAPI (Python 3.11)
- **Frontend:** Next.js + React + TypeScript
- **Database:** PostgreSQL (SQLite for development)
- **Vector Search:** FAISS/ChromaDB for RAG
- **Task Queue:** Celery + Redis
- **Containerization:** Docker + Docker Compose
- **CI/CD:** GitHub Actions

## Quick Start

1. Clone the repository
2. Copy `.env.example` to `.env` and configure your environment variables
3. Run `docker-compose up --build` to start all services
4. Access the application at `http://localhost:3000`

## Submission Deliverables

This repository contains all required deliverables for the assignment:

- ✅ **Source Code:** Complete implementation in `/backend`, `/frontend`, `/agent`
- ✅ **System Design Document:** `/docs/system_design.md`
- ✅ **LLM Interaction Logs:** `/docs/interaction_logs.md`
- ✅ **Demo Documentation:** `/docs/demo_steps.md`
- ✅ **Security Documentation:** `/docs/security.md`

### Optional Demo
- Demo screenshots and video walkthrough available in `/docs/demo/`

## Assignment Submission

Please email the repository URL to the assignment submission addresses listed in the assignment PDF.

---

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/yourusername/assignment-agent)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
