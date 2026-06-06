---
---

--- Before Day-3 ---
I already knew I had some exposure to Python, but I was not comfortable with running scripts from the terminal or managing packages properly.
--- 

## Day-3 Checklist

- [x] I can run a Python script using `uv run script.py` without setting up a local virtual environment
- [x] I know where the temporary virtual environment is created when running the `uv add --script script.py pandas` command followed by `uv run script.py`
- [x] I can create a new Python project using `uv init` and understand what `pyproject.toml` is used for
- [x] I can add a dependency (e.g., `requests`) using `uv add` and see it reflected in the lockfile
- [x] I can create a traditional virtual environment using `uv venv` and know when to use it
- [x] I understand why installing packages globally with `pip install` is a bad habit
- [x] I can open a project in VS Code, select the correct Python interpreter, and run code from the integrated terminal
- [x] I know the difference between a `.py` script and a `.ipynb` notebook, and when to use each

--- After Day-3 ---
I learned these things as well, apart from the checklist 
Global package installation can create dependency conflicts between projects.
Virtual environments isolate project dependencies and make projects reproducible.
uv is a modern replacement for pip, venv, and related tools.
pyproject.toml stores project metadata and dependency information.
uv.lock ensures that everyone working on a project uses the same package versions.
uv run automatically uses the correct environment without manual activation.
VS Code can be configured to use a project's .venv interpreter for development.
Notebooks are useful for exploration, while Python scripts are better for reusable and production-ready code.
uv sync can recreate a project's environment from its configuration files.
---

--- Feedback (Suggestions for the TDS Team) ---
This is my feedback 
The session was well structured and easy to follow.
The comparison between global package installation and virtual environments helped clarify why project isolation is important.
---

---
---

You can write your personal notes here; they will not be parsed and are for your own reference.
