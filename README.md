# OpenAI-SDK-Labs

This repository is a comprehensive collection of beginner-friendly labs designed to master the **OpenAI Agents SDK**. It covers everything from basic initialization to advanced tool integration and local model orchestration.

---

## Overview

The labs in this repository provide a structured path for developers to build autonomous AI agents. We focus on transitioning from static LLM prompts to dynamic agents capable of reasoning, using tools, and running on local infrastructure.

### Labs Included

* **01_agents_sdk_basics**: Introduction to the SDK, environment setup, and creating your first functional agent.
* **02_creating_agents**: Deep dive into agent architectures, defining system instructions, and managing agent personas.
* **03_ollama_with_agents_sdk**: Integrating local LLMs via **Ollama** to run agentic workflows privately and cost-effectively.
* **04_tools_mastery**: The "hands" of the agent—defining Python functions as tools, handling arguments, and executing complex multi-step tasks.

---

## Getting Started

### Prerequisites
* Python 3.10+
* An OpenAI API Key (for cloud-based labs)
* Ollama installed (for Lab 03)

### Installation
This project uses `uv` for dependency management.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/PatheticUser/OpenAI-SDK-Labs.git
    cd OpenAI-SDK-Labs
    ```

2.  **Sync dependencies:**
    ```bash
    uv sync
    ```

3.  **Configure Environment:**
    Create a `.env` file and add your credentials:
    ```env
    OPENAI_API_KEY=your_key_here
    ```

---

## Usage

To run a specific lab, use the `uv run` command:

```bash
# Example: Running the Tools Mastery lab
uv run python 04_tools_mastery/main.py
```

---

## Key Learnings
* **Local Inference**: Learned how to swap cloud providers for local models using the same SDK logic.
* **Functional Tools**: Developed custom tools that allow agents to interact with the real world (file systems, APIs, etc.).
* **Agentic Logic**: Understood the "Plan -> Act -> Observe" cycle that defines modern AI agents.

---

## License
Distributed under the MIT License. See `LICENSE` for more information.

**Maintained by [PatheticUser](https://github.com/PatheticUser)**