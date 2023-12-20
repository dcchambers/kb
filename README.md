# kb

> [!NOTE]
> These notes have been moved to Obsidian and are published via Obsidian Publish.
> They are now available here: https://publish.obsidian.md/dakota
>
> This repo was archived on 20 December 2023.

---

This is my public knowledge base/wiki/digital garden.

It's a growing collection of notes, lists, and knowledge that I find useful.
Maybe you will too.

Published at: [kb.chambers.io](https://kb.chambers.io)

## Develop Locally

- Requires [💎 `ruby`](https://www.ruby-lang.org/en/)
  - I recommend using [`rbenv`](https://github.com/rbenv/rbenv), although there are [several options](https://github.com/rbenv/rbenv/wiki/Comparison-of-version-managers) for managing your local ruby version.
  - See [`.ruby-version`](.ruby-version)
- Requires [`bundler`](https://bundler.io/)

1. Run:
    ```
    bundle install
    bundle exec jekyll s --livereload
    ```
2. Go to http://127.0.0.1:4000/ in your browser.
