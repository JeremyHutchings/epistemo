# Epistemo

**Epistemo** is a local-first knowledge engine designed to help teams retain, explain, and rediscover technical and product decisions over time.

Rather than relying on traditional, decaying documentation, Epistemo continuously ingests structured Markdown notes, code, and relevant team discussions to build a living system of knowledge. Its goal is to make it possible to ask natural language questions such as:

- "Why was this approach chosen?"
- "Who owns this system or decision?"
- "What are the implications of this change?"

## Objectives

- 📥 **Ingest human-readable Markdown** — structured templates for meeting notes, architecture decisions, product input, and rationale.
- 🧠 **Understand source code context** — augment understanding with real code to explain behaviour and decisions.
- 💬 **Track team conversations** — monitor channels (e.g. Slack) to identify captured decisions and rationale.
- ❓ **Answer questions naturally** — allow team members to query the system about how and why decisions were made.
- 🔐 **Fully offline and self-hosted** — designed from the ground up for local use, without relying on third-party services.

## Status
This is an early-stage prototype and research project.


## Using Poetry

To manage dependencies and run your project, you can use the Poetry package manager. Below are the steps to get started:

### Installation

First, install Poetry by following the instructions on the [official Poetry website](https://python-poetry.org/docs/#installation).

### Setting Up the Project

Once Poetry is installed, navigate to the project directory and install the dependencies:

```sh
poetry install
```

### Running the Project
To run the Embedder, you can use the following command:

```sh
poetry run python src/embedder/main.py
```

### Adding Dependencies
If you need to add new dependencies, you can do so using the following command:

```sh
poetry add <package-name>
```

For development dependencies, use:

```sh
poetry add --dev <package-name>
```

