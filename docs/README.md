# Docs

## Requirements

- `mkdocs`
- `mike`

### Installation of mkdocs insiders with pip3

You need `pip3` on your machine.

- Go to https://github.com/settings/tokens
- Click on Generate a new token
- Enter a name and select the `repo` scope
- Generate the token and store it in a safe place

Material for MkDocs Insiders can be installed with pip:

```sh
pip3 install git+https://${GH_TOKEN}@github.com/bamlab/mkdocs-material-insiders.git
```

The GH_TOKEN environment variable must be set to the value of the personal access token you generated in the previous step. Note that the personal access token must be kept secret at all times, as it allows the owner to access your private repositories.

### Installation of mike with pip3

```sh
pip3 install mike
```

## Website

The website is hosted by GitHub pages.

## How to create/update a new version of the doc website

`mike deploy X.Y`

Replace X.Y with a major and minor.

## How to set the default website

`mike set-default X.Y`

## How to deploy the docs

`git push origin gh-pages`

## Iterate on docs and previw locally

`mkdocs serve`

## Preview locally the final documentation website

`mkdocs serve`

