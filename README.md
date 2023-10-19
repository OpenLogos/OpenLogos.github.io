# OpenLogos docs

This repo hosts the OpenLogos documentation that can be accessed as a webpage at https://openlogos.github.io/


## How to contribute
All documentation is in rst format inside the `docs/` folder.
Once the docs are merged into the `main` branch Github Action deploys it to `gh-pages` branch automatically


## View documentation locally

To preview documentation locally, few dependencies needs to be installed:

### Dependencies
Ubuntu:
```
sudo apt-get install -y python3-sphinx python3-sphinx-rtd-theme
```

Arch:
```
sudo pacman -S python-sphinx python-sphinx_rtd_theme
```

For other platforms, see [Getting started with sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html).

### Build

To build the documentation, go into the `docs/` folder and run `make html`:

```
cd docs/
make html
```

This will generate `_build` folder inside the `docs/`, and you can just open it up:

```
xdg-open _/build/html/index.html
```
