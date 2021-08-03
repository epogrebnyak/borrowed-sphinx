# Examples of [Sphinx](https://www.sphinx-doc.org/en/master/) documentation

## Rules

Before starting make sure you understand:

- source: markdown, restructured text (rst)
- output: html, pdf
- code docstrings
- source (rst, markdown) -> theme -> config -> output (html, pdf)

Essence:

- `sphinx-build` reads source files in rst or markdown format and renders
  html documentation from them using a provided theme and other configuration
  parameters
- sphinx adds own directives to rst that allow more control over
  documents structure and content
- sphinx can also produce documentation in latex that build to PDF

Themes:

- `read the docs` is a popular theme for sphinx, but there are many others.
  `pydata` is a modern documentation theme for sphinx.

Directives:

- `toctree` directive is central to sphinx - it builds document tree, so that
  navigation works
- `autodoc` is another key directive that collects docstrings from code.
  This is how documentation is auto-generated.

conf.py:

- `conf.py` is a python script that is used by sphinx-doc for configuration
- `conf.py` can be hand-written with just few lines or auto-generated, with tons
  of options that are hard to understand

## What may be difficult about sphinx

- sphinx consists of several sepearte command-line tools
- make scripts intended to help, but also obfuscate what and how work
- configuration files autogenerated with `sphinx-quickstart` are a bit bloated
- there are also many directives besided `toctree` and `autodoc`
- rst harder than markdown, even though more powerful
- there is a search engine under same name sphinx
- sphinx is difficult to rememder and type correctly

## Examples

`Examples` folder has four self-contained simple examples of sphinx-doc.
Change directory to example folder of interest and run:

```console
sphinx-build .  site
start site/index.html
```

Folders:

1. `minimal`: conf.py + index.rst + rtd theme
2. `pages`: `toctree` directive, more pages and markdown parser
3. `pydata`: pydata theme and two toc levels
4. `autodoc`

## Docs and conf.py examples by project

<table>
<thead>
<tr class="header">
<th>Project</th>
<th>Source folder</th>
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

<tr>
<td><p>cakephp</p></td>
<td><p><a href="https://github.com/jumoyz/cakephp/tree/081454224a415f9b9c8d5892f126612b00fb5146/en">docs</a></p></td>
<td><p><a href="https://github.com/jumoyz/cakephp/blob/081454224a415f9b9c8d5892f126612b00fb5146/en/conf.py">conf.py</a></p></td>
</tr>

</tbody>
</table>

## Read more

- [minimalsphinx](https://github.com/melissawm/minimalsphinx) by Melissa Weber Mendonça

- nanotune (unofficial):
  - [website](https://microsoft.github.io/nanotune/api/index.html)
  - [docs](https://github.com/microsoft/nanotune/tree/docs/docs)

## Photo credits

Sphinx cat photos by

- [Max Simonov, via Unsplash](https://unsplash.com/photos/fU4YA9w5taw)
- [Simona Melegová, via Unsplash](https://unsplash.com/photos/wIZVx0dz3Ok)
