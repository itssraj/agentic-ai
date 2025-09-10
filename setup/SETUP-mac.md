# 🚀 Agentic AI Course Setup Guide (Mac)

Hellooooo everyone! Ready to get your Agentic AI environment up and running on Mac? Follow this step-by-step guide and you’ll be coding agents in no time. Let’s dive in!

---

## 1. Pre-requisites

Before we get started, let’s make sure you have all the right tools:

### a. Download and Install Git
- Git is usually pre-installed on Mac! Check by running:
  ```bash
  git --version
  ```
- If not installed, get it via [Homebrew](https://brew.sh/) if you are on a Mac:
  ```bash
  brew install git
  ```
- Or navigate to the official [Git](https://git-scm.com/downloads) downloads

### b. Download and Install UV
- [UV Installer](https://docs.astral.sh/uv/getting-started/installation/)
- Verify install:
  ```bash
  uv --version
  ```

### c. Download and Install an IDE
- [Cursor](https://www.cursor.com/) or [VS Code](https://code.visualstudio.com/)
- Download, install, and open your favorite editor.

---

## 2. GitHub Repo Setup

Let’s grab the course materials!

### a. Fork the Repo
- Go to [Agentic AI GitHub Repo](https://github.com/SuperDataScience-Community/agentic-ai)
- Click **Fork** (top right) to create your own copy.

### b. Clone to Your Machine
- Open your Terminal.
- Navigate to your projects directory:
  ```bash
  cd ~/Projects
  ```
- Clone your forked repo:
  ```bash
  git clone https://github.com/<your-github-username>/agentic-ai.git
  ```
- Enter the repo folder:
  ```bash
  cd agentic-ai
  ```

---

## 3. Setup Environment Using UV

Time to install dependencies and set up your virtual environment!

- In the repo directory, run:
  ```bash
  uv sync
  ```
- This creates a virtual environment and installs all required packages from `requirements.txt` and `environment.yaml`.

---

## 4. Setup Environment Variables

You’ll need API keys for OpenAI, Gemini, and Anthropic. Here’s how:

### a. Get Your API Keys
- [OpenAI](https://platform.openai.com/api-keys)
- [Anthropic](https://console.anthropic.com/settings/keys)
- [Gemini](https://aistudio.google.com/app/apikey)

### b. Store Keys in `.env` File
- Open `.env` in your editor and paste your API keys:
  ```env
  OPENAI_API_KEY=sk-...
  GEMINI_API_KEY=...
  ANTHROPIC_API_KEY=...
  ```

---

That’s a wrap for your Mac setup, ladies and gentlemen 🎉 Now it’s your turn — I really can’t wait to see what you build!
