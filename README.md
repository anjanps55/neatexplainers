# Neat Explainers

Neat Explainers is a Codex skill for designing and generating sparse, hand-drawn English article illustrations on a pure white 16:9 canvas.

It turns one key judgment, process, structure, state, or metaphor from an article into a clean but strange explanatory image: black wobbly line art, lots of empty space, sparse red/orange/blue handwritten English annotations, and one expressive white human character doing the core conceptual action.

## Credit

Adapted from [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations) by Ian.

This project keeps Ian's MIT license notice and derived-project attribution. It changes the default language, character design, and prompt constraints for English article explainers.

## Install

Clone this repo and copy it into your Codex skills directory:

```bash
git clone https://github.com/anjanps55/neatexplainers.git
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills/expressive-white-article-illustrations"
rsync -a --exclude .git neatexplainers/ "${CODEX_HOME:-$HOME/.codex}/skills/expressive-white-article-illustrations/"
```

Use it in Codex:

```text
Use $expressive-white-article-illustrations to design and generate a set of sparse absurd illustrations for this English article.
```

## What It Produces

- 16:9 horizontal English article body illustrations
- Shot lists for articles, essays, posts, Notion docs, workflow notes, and methodology content
- Pure white backgrounds, black hand-drawn wobbly line art, and sparse red/orange/blue handwritten labels
- PNG images saved under `assets/<article-slug>-illustrations/`

## License

MIT. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).
