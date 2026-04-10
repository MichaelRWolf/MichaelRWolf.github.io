# CLAUDE.md — MichaelRWolf.github.io

Jekyll blog repo. Live site: <https://MichaelRWolf.github.io>

## Key Rule

**Do not write or edit post content here.** Posts are authored in the
`writing/` repo and copied here as a deploy step. Edits made directly in
`_posts/` will be overwritten on next publish.

To update a post: edit the source file in `writing/`, then re-run the
publish workflow.

## Publishing Workflow

Full workflow (symlinks, front matter, commit conventions, two-repo coordination):
see [writing/HOWTO\_publish\_blog\_post.md](https://github.com/MichaelRWolf/writing/blob/main/HOWTO_publish_blog_post.md)

Blog repo bookkeeping steps only: see [README.md](README.md#publishing)

## Local Preview

```shell
./bin/serve_localhost_4000
```

Or with drafts and live reload:

```shell
bundle exec jekyll serve --livereload --drafts
```

Preview at <http://localhost:4000>

## Structure

| Path | What it is |
| --- | --- |
| `_posts/` | Published posts (deployed from `writing/`; do not edit directly) |
| `_drafts/` | Local drafts not yet in `writing/` — move to `writing/` before publishing |
| `_layouts/` | Jekyll layout overrides |
| `assets/` | Images and static files |
| `bin/` | Helper scripts (e.g., `serve_localhost_4000`) |
