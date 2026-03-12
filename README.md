# MichaelRWolf.github.io

- Repo: <https://github.com/MichaelRWolf/MichaelRWolf.github.io>
- Live site: <https://MichaelRWolf.github.io>
- Local preview: <http://localhost:4000>

## Local preview

```shell
./bin/serve_localhost_4000
```

This script uses `chruby-exec` to run each command under Ruby 3.1.3, installs
`bundler`, runs `bundle install`, starts Jekyll, and opens the browser.

`.ruby-version` is also present for tools that read it automatically (Cursor's
Ruby LSP, chruby `auto.sh`).

For drafts and live reload, run Jekyll directly:

```shell
bundle exec jekyll serve --livereload --drafts
```

## Theme

This site uses [minima](https://github.com/jekyll/minima) — the default Jekyll
blog theme. It provides `post`, `page`, and `default` layouts.

## Dependency maintenance

Update all gems to their latest allowed versions:

```shell
bundle update
```

Check for outdated gems:

```shell
bundle outdated
```

After updating, verify locally with `./bin/serve_localhost_4000` before
committing `Gemfile.lock`.

Update minima alone:

```shell
bundle update minima
```

## Publishing

Push `main` to GitHub. GitHub Pages builds and deploys automatically.
