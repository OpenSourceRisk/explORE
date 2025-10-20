<p align="center">
    <a href="https://github.com/Devin-Cook/explORE-AI"><img src="./assets/explore_logo.svg" alt="explORE-AI Logo" width="5000"></a>
</p>

# explORE-AI — A Specialized Fork of Aider for Open Source Risk Engine (ORE)

<p align="center">
  <em>Built upon the amazing foundation of <a href="https://aider.chat/">Aider</a></em>
</p>

**explORE-AI** helps you navigate, understand, and contribute to the **Open Source Risk Engine (ORE)** codebase. Originally derived from the powerful [Aider](https://github.com/Aider-AI/aider) AI pair-programming tool, this fork is tailored for **domain-specific insights** into ORE. If you find Aider useful for general purposes, please check out their project. For **ORE-focused** development, read on!

<p align="center">
  <img
    src="./assets/terminal.svg"
    alt="explORE-AI screencast"
  >
</p>

<p align="center">

## Why explORE-AI?

[Open Source Risk Engine (ORE)](https://github.com/OpenSourceRisk/Engine) is a large and sophisticated library for risk analytics, financial instrument modeling, and more. Diving into ORE can be **intimidating** due to its size and complexity.

**explORE-AI**:

- Leverages **Aider**’s AI pair-programming features and **tailors** them for ORE development.
- Provides specialized insights into ORE’s architecture, including analytics, classes, and data relationships.
- Helps generate targeted refactors, test scaffolds, or risk analytics examples relevant to ORE.

We owe a **huge thanks** to [Aider](https://github.com/Aider-AI/aider) for providing the robust foundation that made this fork possible.

## Features

- 🏦 **ORE-Specific Insights** — **explORE-AI** can reference and analyze ORE’s specific code structure, giving more precise guidance.
- 🗺️ **Codebase Mapping** — Just like Aider, but with a deeper understanding of the ORE ecosystem.
- 🧠 **[Cloud and Local LLMs](https://aider.chat/docs/llms.html)** — explORE-AI is mainly developed and tested with GPT variants, however other models supported by aider may work.


# Getting Started with explORE-AI

Follow the instructions below to clone, install, and use explORE-AI effectively.

## Directory Structure

Ensure your directory is structured correctly for explORE-AI to function properly:

```
root/
├── Engine/
└── explORE-AI/
```

This layout enables explORE-AI to locate the ORE directory correctly.

## Cloning the Repository

Clone the explORE-AI repository into the **root** directory using the following command:

```bash
git clone https://github.com/Devin-Cook/explORE-AI.git
```

## Installation

Navigate to your `root` directory (containing both the `Engine` and `explORE-AI` directories) and install explORE-AI by running:

```bash
python -m pip install ./explORE-AI
```

## Usage

After installation, you can interact with explORE-AI in several ways:

### 1. Command-Line Interaction

To start the chat via command-line mode, use:

```bash
explore-ai --openai-api-key=OPENAPI_KEY
```

Replace `OPENAPI_KEY` with your actual OpenAI API key.

### 2. GUI Mode

To launch the graphical user interface (GUI) via Streamlit, execute:

```bash
explore-ai --openai-api-key=OPENAPI_KEY --gui
```

### 3. GUI with Userguide Materials

To initialize the GUI along with the Userguide materials, run:

```bash
explore-ai --openai-api-key=OPENAPI_KEY --userguide --gui
```

## Additional Notes

- Ensure you are in the `root` directory containing both `Engine` and `explORE-AI` when running installation and other commands.
- Verify the validity of your OpenAI API key.
- If you encounter any issues, confirm your directory structure and dependencies installation.
