# DLWAY

**Data to deployed model, in one browser tab.**

DLWAY (Deep Learning, Your Way) is a local-first workspace for the whole data and machine learning job: bring data in, clean and explore it, build and train models, make dashboards, automate the repeatable parts and ship the result. It runs in your browser, on your own hardware, and there is nothing to install.

[Open the Studio](https://dlway.org/studio) · [Documentation](https://dlway.org/docs) · [Tutorials](https://dlway.org/tutorials) · [Report a bug or suggest an idea](https://dlway.org/feedback)

---

## Why it exists

A normal workflow is spread across a notebook or editor, a visual pipeline tool, a BI tool, a browser tab for Kaggle or Hugging Face and a paid cloud notebook underneath. Every hop means exporting, re-uploading and re-explaining the data, and the compute bill and the privacy risk come along with it.

DLWAY keeps all of it in one project, and the heavy work happens on the machine in front of you.

## What is inside

| Module | What it does |
|---|---|
| Code editor | Multi-file editor with a terminal. Python runs in the browser through Pyodide, with JavaScript and TensorFlow.js alongside. |
| Data Hub | Files, folders, URLs, live databases, Kaggle and Hugging Face, with profiling, quality checks, versions and lineage. |
| PrepFlow | Visual data preparation and exploratory analysis, compiled to SQL and run in DuckDB where it can. |
| Model Builder | A canvas for neural networks that generates real TensorFlow.js or PyTorch code. |
| Train and Fine-Tune | Live loss curves and hardware use while training, then evaluation and fine-tuning. |
| Dashboard | Drag and drop charts, calculated fields, parameters and stories. |
| Pipelines | Scheduled and event-driven jobs, without a separate orchestrator. |
| Research | Turn a paper into a runnable project, with the defaults visible and editable. |
| Deployment | Package a model for the browser or a server, with checks before you ship. |
| AI Copilot | A coding assistant that works inside the project, with your own provider key. |

## Local-first

- Your datasets, code and models stay on your machine. Data only leaves when you choose it: a Kaggle or Hugging Face import, a live database connection, a remote Jupyter server or an AI Copilot request.
- No installer and no admin rights, so it works on locked-down school, lab and company computers.
- No metered compute. Training runs on your own CPU or GPU, with no notebook session that times out in the middle of a run.

## Where things stand

| Product | State |
|---|---|
| Web Studio | Live |
| Desktop IDE (native, with real Python environments and local CUDA) | In development |

Both are meant to share one project format, so a project can move between them without a conversion step.

## Built with

Next.js, React and TypeScript. Pyodide, TensorFlow.js and DuckDB-WASM do the work in the browser. Monaco is the editor and React Flow draws the canvases.

## Talk to us

DLWAY is built by two data science students, and every bug report and idea gets read.

- Bugs and suggestions: [dlway.org/feedback](https://dlway.org/feedback) or support@dlway.org
- Everything else: info@dlway.org
