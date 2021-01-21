# Examples for Sphinx documentation

## Source folders and conf.py

<table>
<thead>
<tr class="header">
<th>Project</th>
<th>docs folder</th>
<th>conf.py</th>
</tr>
</thead>
<tbody>
<tr>
<td><p>Hypermodern Packaging</p></td>
<td><p><a href="https://github.com/cjolowicz/cookiecutter-hypermodern-python/tree/master/%7B%7Bcookiecutter.project_name%7D%7D/docs">docs</a></p></td>
<td><p><a href="https://github.com/cjolowicz/cookiecutter-hypermodern-python/blob/master/%7B%7Bcookiecutter.project_name%7D%7D/docs/conf.py">conf.py</a></p></td>
</tr>
<tr>
<td><p>IASA message_ix</p></td>
<td><p><a href="https://github.com/iiasa/message_ix/tree/master/doc">docs</a></p></td>
<td><p><a href="https://github.com/iiasa/message_ix/blob/master/doc/conf.py">conf.py</a></p></td>
</tr>
<tr>
<td><p>pydata theme</p></td>
<td><p><a href="https://github.com/pandas-dev/pydata-sphinx-theme/blob/master/docs/">docs</a></p></td>
<td><p><a href="https://github.com/pandas-dev/pydata-sphinx-theme/blob/master/docs/conf.py">conf.py</a></p></td>
</tr>
<tr>
<td><p>librosa</p></td>
<td><p><a href="https://github.com/librosa/librosa/blob/main/docs/">docs</a></p></td>
<td><p><a href="https://github.com/librosa/librosa/blob/main/docs/conf.py">conf.py</a></p></td>
</tr>
</tbody>
</table>

## [Minimal example](https://gitlab.com/epogrebnyak/sphinx-minimal/)

**conf.py.**

```python
project = "Seemingly Simple Project"
author = "I.M. Coder"
copyright = f"2021, {author}"
extensions = ["sphinx_rtd_theme"]
html_theme = "sphinx_rtd_theme"
```

**index.rst**

```rst
Main page
=========

This is documentation.
```

## Photo credit

Sphinx cat photo by [Max Simonov, via Unsplash](https://unsplash.com/photos/fU4YA9w5taw)
