# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This repo holds starting code for DS1001 course project labs (LABS3, LABS6, LABS9, LABS12). It is a student's coursework repo, not a production codebase — expect it to grow incrementally as new labs are assigned, mostly as Jupyter notebooks.

Currently only LABS-03 (`LABS-03_Systems.ipynb`) exists. It's an environment-setup notebook: it prints a hello-world check, imports pandas, and has a `pd.read_csv()` call the student is meant to fill in with a real data file path.

## Environment

- Dependencies are listed in `requirements.txt` and installed with `pip install -r requirements.txt`.
- Notebooks are run through VS Code's Jupyter extension (see `.vscode/extensions.json` for the recommended extension set: Jupyter, Pylance, Python, debugpy).
- There is no build, lint, or test tooling configured in this repo. Don't assume a test suite or linter exists — verify by running the specific notebook cell instead.

## Working in this repo

- Each lab is a self-contained notebook; don't assume shared modules or utilities exist across labs unless you find them.
- When a notebook cell has a placeholder comment (e.g. "add your data file path to this line!"), that's an intentional exercise for the student — fill it in based on context/instructions rather than inventing unrelated logic.
