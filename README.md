# 343mps.io website

<https://343mps.io>

## Working locally

First, follow the instructions to install Jekyll, Ruby as needed from https://jekyllrb.com/docs/ .

To run a local dev server:

```sh
# Install dependencies
$ bundle install --path vendor/bundle
# Run the dev server
$ bundle exec jekyll serve
```

Access the server at <http://127.0.0.1:4000>.

Content changes are automatically reloaded as you make changes.  Changes to config files (e.g.
`_config.yml`) require a server restart before they'll take effect.

## Publishing

The `main` branch is automatically built and synced to <https://343mps.io>.
