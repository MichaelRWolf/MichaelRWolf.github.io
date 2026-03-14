# MichaelRWolf.github.io

- Repo: <https://github.com/MichaelRWolf/MichaelRWolf.github.io>
- Live site: <https://MichaelRWolf.github.io>
- Local preview: <http://localhost:4000>

## Software Crafters UnConference — Spring 2026

Wolf, M. (2026, March 14). _Spent a day at the Software Crafters UnConference last month_ [LinkedIn post]. LinkedIn. <https://www.linkedin.com/posts/mrwolf_softwarecraftsmanship-unconference-agile-activity-7438657634280341504-cg0h>

Wolf, M. (2026, March 14). _Software Crafters UnConference — Spring 2026_ [Blog post]. michaelrwolf.github.io. <https://michaelrwolf.github.io/2026/03/14/software-crafters-unconference/>

| Asset              | Type     | Events repo                                                                                          | github.io repo                                                                                                                                      |
| ------------------ | -------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Blog post          | Markdown | `2026-02-06_Software_Crafters_Unconference/software-crafters-unconference.md`                        | [\_posts/2026-03-14-software-crafters-unconference.md](_posts/2026-03-14-software-crafters-unconference.md)                                         |
| LinkedIn post      | Text     | `2026-02-06_Software_Crafters_Unconference/software-crafters-unconference_linkedin.txt`              | —                                                                                                                                                   |
| Visual notes image | Image    | `2026-02-06_Software_Crafters_Unconference/software-crafters-unconference-visual-notes-1200x628.png` | [software-crafters-unconference-visual-notes-spring-2026-1200x628.png](images/software-crafters-unconference-visual-notes-spring-2026-1200x628.png) |

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
