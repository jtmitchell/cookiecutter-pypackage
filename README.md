# cookiecutter-pypackage

Cookiecutter template for a Python package. 

Forked from https://github.com/audreyr/cookiecutter.
* use markdown README and GPL

* Free software: BSD license
* Vanilla testing setup with `unittest` and `python setup.py test`
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_

## Usage

Generate a Python package project

```
    cookiecutter https://github.com/jtmitchell/cookiecutter-pypackage.git
```

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist: 
  https://gist.github.com/audreyr/5990987
