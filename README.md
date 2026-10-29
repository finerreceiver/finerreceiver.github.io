# finerreceiver.github.io

Source of the [LMT-FINER project website](https://finerreceiver.github.io/), built with [Hugo](https://gohugo.io/) and the [Hugo Blox](https://hugoblox.com/) theme (formerly Wowchemy).

## Where things are

| Path | Contents |
|---|---|
| `content/home/` | Top page sections: slider, news, about, team (`*.md` = English, `*.ja.md` = Japanese) |
| `content/page/` | Science, Receiver, Publications and FAQ pages |
| `content/post/YYYY-MM-DD/` | News posts (`index.md` and `index.ja.md`) |
| `assets/media/` | Site images (slider photos, icon, `sharing.jpg` for social-media previews) |
| `config/_default/` | Site settings, menus and languages |

## How to update

1. Edit the Markdown files on a branch and open a pull request.
2. The **Tests** workflow builds the site for every pull request.
3. After merging into `main`, the **GitHub Pages** workflow publishes the site automatically.

## Local preview

Install Hugo extended (version in `.github/workflows/gh-pages.yaml`) and Go, then run `hugo server` and open http://localhost:1313/.
