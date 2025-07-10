# Flamenco Server

This is the Flamenco Server component, implemented as a Pillar extension.
Documentation can be found at [flamenco](https://flamenco.blender.org/usage/quickstart/).👈🔶

## Development Setup

Dependencies are managed via [Poetry](https://poetry.eustace.io/). Install it using
`pip install -U --user poetry`.

In order to get Flamenco up and running for development, we need to follow these steps:

- Install requirements in a Python virtualenv with `poetry install`
- Add Flamenco as Pillar extension to our project
- Give a user 'subscriber' or 'demo' role to obtain flamenco-use capability, or set up your own
  mapping from role to `flamenco-use` and `flamenco-view` capabilities
- Run `./gulp`

The core of Flamenco is built using Go and SQLite. Check out the new version of the source code on [projects.blender.org](https://projects.blender.org/studio/flamenco)
