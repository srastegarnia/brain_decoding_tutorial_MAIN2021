# brain_encoding_decoding

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/srastegarnia/brain_decoding_tutorial_MAIN2021/main?labpath=notebooks%2Fmultiple_decoders_haxby_tutorial.ipynb)

This is a jupyter book presenting an introduction to brain encoding and decoding using python. It is rendered on [srastegarnia.github.io/brain_decoding_tutorial_MAIN2021](https://srastegarnia.github.io/brain_decoding_tutorial_MAIN2021).

### Build the book

If you want to build the book locally:

- Clone this repository
- Run `pip install -r binder/requirements.txt` (it is recommended to run this command in a virtual environment)
- For a clean build, remove `_build/`
- Run `jupyter-book build .`

An html version of the jupyter book will be automatically generated in the folder `_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. Navigate to your local build and run:
- `ghp-import -n -p -f _build/html`

This will automatically push your build to the `gh-pages` branch. More information on this hosting process can be found [here](https://jupyterbook.org/publish/gh-pages.html).
