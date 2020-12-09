# Developing for the trestle documentation website

This page describes the developing for the trestle website.

## Build system and local testing of the website.

Trestle has adopted the `mkdocs` system to generate this website using a small number of extensions to mkdocs. The
website can be viewed locally from a clone of the `compliance-trestle` repo by running `make docs-site` in the root
directory bringing the website up at `https://localhost:8000`. If you experience issues run `make develop` to ensure the
appropriate markdown extensions are in your python environment.

All documentation assets are stored within the `./docs` folder. The exception being `mkdocs.yml` which configures the
documentation tree. Before opening a PR users should ensure:

- No warnings are generated by mkdocs
- All markdown documents within `./docs` are included in the website navigation defined in `mkdocs.yml`

### Github project documents

A small number of files within github projects are used by github for specialised index / search (such as `README.md`,
`CODE_OF_CONDUCT.md` etc). To avoid duplication these documents are referenced if included in the website using `markdown-include`.
See `docs/mkdocs_code_of_conduct.md` within the codebase for an example.

### API reference files

a

### Command line documentation

## Contributing changes

## Expectations on developers of trestle functionality