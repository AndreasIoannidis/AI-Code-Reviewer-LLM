# AI-Powered Code Reviewer Node.js / Python 🤖🛠️

An automated code review tool that leverages Large Language Models (LLMs) to analyze source code files, detect potential bugs, evaluate security vulnerabilities, and suggest refactoring improvements based on standard coding best practices.

---

## 📌 Project Overview

Manual code reviews are vital but time-consuming. This project automates the first line of defense in the development lifecycle by building an automated pipeline that feeds code updates to an LLM, processes the architectural context, and returns targeted, actionable feedback directly to the engineer.

It serves as a foundation for building custom CI/CD AI agents that can run static and semantic analysis before human reviews.

---

## ⚙️ Tech Stack & Architecture

*   **Core Engine:** Node.js / Python *(Κράτα ή άλλαξε ανάλογα με το τι χρησιμοποίησες)*
*   **AI Integration:** OpenAI API (GPT-4o) / Anthropic API (Claude 3.5 Sonnet) / Google Gemini API via official SDKs.
*   **Prompt Engineering:** Structured system prompts designed to enforce syntax constraints and reduce hallucinations.
*   **Data Format:** JSON-structured model outputs for programmatic parsing and easy integration.

---

## 🚀 Key Features Implemented

*   **Multi-Aspect Analysis:** Evaluates source code across four main pillars:
    1.  **Bug Detection:** Logic errors, edge cases, and memory leak vulnerabilities.
    2.  **Security Audit:** Hardcoded credentials, SQL injection risks, and insecure packages.
    3.  **Code Quality:** Adherence to design patterns, readability, and DRY (Don't Repeat Yourself) principles.
    4.  **Performance:** Complexity analysis ($O(n)$ bottlenecks) and optimization recommendations.
*   **Context-Aware Prompting:** System configuration prompts that instruct the LLM to behave strictly as an unbiased Senior Software Engineer.
*   **API-Driven Architecture:** Designed to easily hook into pre-commit scripts, local Git hooks, or webhooks.

---



