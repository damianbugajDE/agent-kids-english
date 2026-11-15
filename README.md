## Python Environment & Dependencies

This project uses [uv](https://docs.astral.sh/uv/) for Python environment and dependency management.

### Common Commands

| Operation | Command |
|---|---|
| Add a dependency | `uv add package_name` |
| Remove a dependency | `uv remove package_name` |
| Synchronize dependencies | `uv sync` |
| Start Python interpreter | `uv run python` |
| Run a Python script | `uv run python main.py` |
| Display dependency tree | `uv tree` |

### Additional Information

- `pyproject.toml` stores project configuration and dependencies.
- `uv.lock` stores exact dependency versions to ensure reproducible environments.
- `.python-version` specifies the Python version used by the project.
- `.venv/` contains the virtual environment.

**Note:** You do not need to activate the virtual environment manually when using `uv run`. UV automatically uses the project's environment.