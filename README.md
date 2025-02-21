# Data Formulator: Create Rich Visualizations with AI 🪄

Transform data and create rich visualizations iteratively with AI. Try **Data Formulator** now!

---

## News 🔥🔥🔥

- **[02-20-2025]** Data Formulator 0.1.6 released!  
  - Now supports working with multiple datasets at once! Tell Data Formulator which data tables you'd like to use, and it will join them to create visualizations. 🪄  
  - Update to the latest version to explore new features.

- **[02-12-2025]** More models supported!  
  - Now supports OpenAI, Azure, Ollama, and Anthropic models (powered by [LiteLLM](https://github.com/BerriAI/litellm)).  
  - Recommended models: GPT-4o, Claude-3-5-Sonnet.  
  - Store API keys in `api-keys.env` (see `api-keys.env.template`).  
 

- **[11-07-2024]** Visualization challenges added!  
  - Try out the new visualization challenges with sample datasets.  


- **[10-11-2024]** Python package released!  
  - Install Data Formulator via Python PIP and run it locally.  
  - Experimental feature: Parse and clean messy text or images using AI.  



---

## Overview

**Data Formulator** is an AI-powered Research tool  that helps analysts create rich visualizations by combining natural language inputs and UI interactions. It simplifies data transformation and visualization design, making it easier to explore and understand data.

---

## Get Started

### Option 1: Install via Python PIP

```bash
# Install data_formulator
pip install data_formulator

# Start Data Formulator
data_formulator

# Alternatively, run with a specific port
python -m data_formulator --port 8080


Data Formulator will open in your browser at http://localhost:5000.

Option 2: Codespaces (5 minutes)
Run Data Formulator in GitHub Codespaces with everything pre-configured.
Open in GitHub Codespaces

Option 3: Developer Mode
For full control and customization, follow the DEVELOPMENT.md guide.

Using Data Formulator
Set Up: Provide your OpenAI API key, select a model (e.g., GPT-4o), and choose a dataset.

Create Visualizations:

Choose a chart type and drag-and-drop data fields to specify visual encodings.

Type names of fields that don't exist in the current dataset to trigger AI-powered transformations.

Click Formulate to generate the visualization.

Iterate: Use natural language prompts to refine or create new visualizations.

Developers' Guide
Follow the DEVELOPMENT.md instructions to build custom tools on top of Data Formulator.

Research Papers
Data Formulator 2: Iteratively Creating Rich Visualizations with AI

Data Formulator: AI-powered Concept-driven Visualization Authoring

Contributing
We welcome contributions! Please review our Contributor License Agreement (CLA) and follow the Code of Conduct.

Trademarks
This project may contain trademarks or logos. 




This `README.md` script provides a comprehensive overview of the **Data Formulator** project, including installation instructions, usage guidelines, and contribution details. Let me know if you need further adjustments! 🚀
