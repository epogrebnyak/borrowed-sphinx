# Dry minimum Sphinx example

Based on <https://gitlab.com/epogrebnyak/sphinx-minimal/>

**docs/conf.py** (configuration)

```python
project = "Seemingly Simple Project"
author = "I.M. Coder"
copyright = f"2021, {author}"
extensions = ["sphinx_rtd_theme"]
html_theme = "sphinx_rtd_theme"
```

**docs/index.rst** (contents, or "source")

```rst
Main page
=========

This is documentation.
```

**To run:**

```console
pip install -r requirements.txt
cd examples/minimal
sphinx-build . site
start site/index.html
```
