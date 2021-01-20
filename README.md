[sphinx-doc]: https://www.sphinx-doc.org/en/master/

# 1. Minimal examples

Minimal example of Sphinx documentation setup:

- <https://gitlab.com/epogrebnyak/sphinx-minimal/-/tree/master/docs>

Outputs:

- <https://epogrebnyak.gitlab.io/sphinx-minimal>
- <http://sphinx-minimal.s3-website.eu-central-1.amazonaws.com/>


# 2. Collection 

This is a collection of [sphinx-doc][sphinx-doc] setup examples. It is aimed to make life easier when creating documentation.

## Docs folders and conf.py examples:

- Hypermodern Packaging:
  - [docs](https://github.com/cjolowicz/cookiecutter-hypermodern-python/tree/master/%7B%7Bcookiecutter.project_name%7D%7D/docs)
  - [conf.py](https://github.com/cjolowicz/cookiecutter-hypermodern-python/blob/master/%7B%7Bcookiecutter.project_name%7D%7D/docs/conf.py)  
- IASA message_ix:
  - [docs](https://github.com/iiasa/message_ix/tree/master/doc)
  - [conf.py](https://github.com/iiasa/message_ix/blob/master/doc/conf.py)
- pydata theme:
  - [docs](https://github.com/pandas-dev/pydata-sphinx-theme/blob/master/docs/)
  - [conf.py](https://github.com/pandas-dev/pydata-sphinx-theme/blob/master/docs/conf.py)
- librosa:  
  - [docs](https://github.com/librosa/librosa/blob/main/docs/)
  - [conf.py](https://github.com/librosa/librosa/blob/main/docs/conf.py)
  
## Blogs:

- <https://predictablynoisy.com/posts/2020/sphinx-blogging/>


## Utilities:

- [flinx](https://github.com/osteele/flinx/blob/master/flinx/templates/conf.py.tpl) conf.py generator
- [pyproject.toml - > conf.py](https://github.com/epogrebnyak/weo-reader/blob/master/make_conf.py)


## Comments

sphinx is extemely powerful and versatile, but why using [sphinx-doc][sphinx-doc] is hard?
Possible reasons:

- default setup is complex (tweaking sys.path for discoverability, many options not of use)
- two uses in one: rst source and api documentation, rst directives language + rst as markup 
- you can just easilty get lost in the docs
- [got to learn a lot before even starting](https://twitter.com/mistersql/status/1097238985792016384)
- old project, many old design desisions and documentation

## Credit 

Sphinx photo by [Max Simonov via Unsplash](https://unsplash.com/photos/fU4YA9w5taw)
