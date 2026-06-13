# GemmaX ChatCore

A multimodal AI chat notebook that explores Gemma-based text chat, image understanding, local inference, and tool-style function calling.

## Overview

GemmaX ChatCore is an experimental AI system built to understand how modern generative AI workflows are structured in practice. The project combines cloud model access, notebook-driven experimentation, multimodal prompts, and local inference exploration in one readable workflow.

## Capabilities

- Text-based chat with conversation history.
- Image + text multimodal analysis.
- Cloud inference using the Google GenAI SDK.
- Local Gemma experimentation with KerasHub and JAX.
- Function-calling style utilities, including datetime and currency examples.
- Formatted outputs for clearer notebook demonstrations.

## Repository Structure

```text
GemmaX_ChatCore/
├── GemmaX_ChatCore.ipynb   # Main experiment notebook
├── assets/                 # Demo images for multimodal prompts
├── LICENSE
└── README.md
```

## Tech Stack

- Python
- Jupyter Notebook
- Google GenAI SDK
- Gemma models
- KerasHub
- JAX

## Getting Started

1. Clone the repository.
2. Open `GemmaX_ChatCore.ipynb` in Jupyter, VS Code, or Google Colab.
3. Install the notebook dependencies listed in the setup cells.
4. Add your own API key securely before running cloud inference.

> Security note: do not commit API keys or private tokens to the repository. Prefer environment variables or notebook secrets when running experiments.

## Usage Flow

1. Run the setup cells.
2. Choose cloud inference or local inference sections.
3. Test text chat prompts.
4. Test image analysis using files from `assets/`.
5. Run the function-calling examples.
6. Review the outputs and compare model behavior.

## What This Project Demonstrates

- Understanding of LLM experimentation workflows.
- Practical use of multimodal prompts.
- Ability to structure AI experiments in a reproducible notebook.
- Interest in moving from simple prompts toward more system-like AI behavior.

## Roadmap

- Add a `requirements.txt` file for easier setup.
- Move reusable logic from notebook cells into Python modules.
- Add sample screenshots or output examples.
- Document prompt design choices and model limitations.
- Add a small evaluation section for response quality and failure cases.

## Authors

- Jibitesh Kumar Mishra
- Ankita Singh

## License

This project is licensed under the MIT License.
