# ``mriseqplot``

``mriseqplot`` is a python module to generate and render MRI sequence diagrams with.
It's early days for the project and its main mission now is to provide a simple API
to generate neat tweakable sequence diagrams.

## Installing ``mriseqplot``

``mriseqplot`` is not yet on PyPI, neither it is available through anaconda. To install the module, clone the repository from GitHub

```sh
git clone git@github.com:Sibgatulin/mriseqplot.git
```

and then install via ``pip``

```sh
pip install mriseqplot
```

or if you plan to modify the code, install it in «editable» mode

```sh
pip install -e mriseqplot
```
Furthermore, if you intend to commit to the repository, you'll need ``pre-commit``, so
we recommend you go with the dev ``extra`` requirements (mind no space before ``[``)
and set ``pre-commit`` up:

```sh
pip install -e mriseqplot[dev]
pre-commit install
```

## Contributing to ``mriseqplot``

The project tries to stick with PEP8 and encourages to use ``black`` (see installation
above).
Occasionally, there are some [type hints](https://www.python.org/dev/peps/pep-0484)
but their use is so far... Experimental? 🤔🤷

## License

``mriseqplot`` is licensed under the terms of the MIT license.
Please see the [LICENSE file](https://github.com/Sibgatulin/mriseqplot/blob/master/LICENSE).
