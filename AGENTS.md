# AGENTS.md

- Prefer Polars over pandas for tabular data unless an existing notebook already depends on pandas.
- Keep notebook code readable: use descriptive variable names, not terse mathematical abbreviations.
- Add short, one-line docstrings to every function, class, and method.
- Add type annotations to all function and method arguments.
- Use Markdown cells sparingly. Add them mainly for LaTex equations that are necessary for understanding.
- Keep Markdown commentary terse. Avoid long prose between code cells.
- Put optional or fragile UI imports, especially `ipywidgets`, near the widget cell instead of in the first import cell.
- Do not make widgets required for the rest of the notebook to run.
- Keep a static, non-widget example before any interactive widget version.
- Do not run notebook cells unless explicitly asked.
- When editing notebooks, preserve existing cell structure and outputs unless the task requires changing them.
- Prefer small, focused cells over large mixed-purpose cells. One cell per function or class unless they are tightly coupled.
- Put most logic inside of functions and then call them, rather than working in the global namespace.
- Only variables shared by the entire notebook should be in the global namespace, such as configuration constants and data frames.
