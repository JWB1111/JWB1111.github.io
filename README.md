# Julius Wolf — Portfolio

Jekyll portfolio site. No theme dependency — fully custom CSS.

## Local Development

```bash
# First time only — delete any existing lock file to avoid minima conflicts
rm -f Gemfile.lock

bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000

## Adding Project Content

Each project lives in `_projects/`. Open the `.md` file and fill in the
sections marked with `[Write here...]` comments.

## Deploying to GitHub Pages

Make sure your repo is named `JWB1111.github.io` and push to `main`.
GitHub Pages will build automatically.
