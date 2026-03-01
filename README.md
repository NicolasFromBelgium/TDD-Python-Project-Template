# TDD Python Project Template 🚀

**A professional template to start any Python project using Test Driven Development (TDD)**

This template contains everything you need to practice **real TDD** from the very first commit:

- Modern `src/` project structure
- pre-commit (black + ruff)
- Complete GitHub Actions CI (lint + type checking + tests on Python 3.11/3.12)
- 2 demo tests to force you to follow the Red → Green → Refactor cycle

## The 2 Demo Tests (Essential for Understanding TDD)

1. **`test_project_has_at_least_one_test`** → **Should pass**  
   (There are already 2 tests in the project.)

2. **`test_project_has_new_files`** → **Intentionally fails at the beginning**  
   Clear message:  
   > "Create src/tdd_template/main.py (or any new file) first!  
   > Remember the TDD rule: **Write the TEST before the code!**"

## How to Use This Template

1. Click **"Use this template"** → "Create a new repository" on GitHub
2. Clone your new repository
3. `python -m venv venv && source venv/bin/activate`
4. `pip install -r requirements-dev.txt`
5. `pre-commit install`
6. `git add . && git commit -m "chore: initial TDD template setup"`
7. **Run the tests**: `pytest`

→ First test should work → Basic check for TDD and CI, base requirements are OK if test is passed
→ You will see second test  failing → **this is normal and intentional! TDD principle**

## The TDD Rule

**Red** (write a failing test) → **Green** (write the minimal code to make it pass) → **Refactor**

## Useful Commands

\`\`\`bash
pytest                  # run all tests
pre-commit run --all-files
pytest --cov=src        # with coverage
\`\`\`

This template is open-source (MIT license) – fork it, modify it, and share it!

Made with ❤️ by NicolasFromBelgium (inspired by LongVue)
