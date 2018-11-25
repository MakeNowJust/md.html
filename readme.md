---
title: md.html
---

# :memo: md.html

> Markdown inside HTML

Put the following two magical lines into top of HTML file, then you can write Markdown after this and browser renders Markdown automatically.

```markdown
<!doctype html><meta charset="utf-8"><script src="https://makenowjust.github.io/md.html/main.js"></script><noscript>
<!-- vim: set ft=markdown: -->

# Hello `md.html` World!
```

See [md.html demo](https://makenowjust.github.io/md.html/)!<!-- MARKER -->

## Features

- Don't need preprocessing for rendering Markdown.
- Render soft breaks as `<br>`.
- Emoji support (e.g. convert `:memo:` to 📝)
- Set `target="_blank"` property to external links.
- Math expression support (inline `$...$` and block `$$⏎...⏎$$`) with [KaTeX][]
- Set slug `id` to `h1-6` tags and append anchor icon.
- Syntax highlighting
- Set title via frontmatter `title` property.

**See [examples](./examples/index.html)**!

## Special Thanks

This project is built with many other packages.

- [remark][] and [unified][] families: Markdown to HTML pipeline
- [github-markdown-css][]: Markdown CSS extracted from GitHub
- [highlight.js][]: syntax highlighting library
- [KaTeX][]: math typesetting library
- [gray-matter][]: frontmatter parser
- [babel][]: JavaScript transpiler
- [webpack][]: JavaScript bundler
- [jest][]: test runner
- [maid][]: Markdown task runner
- [prettier][]: opinionated formatter

and all other dependencies... Thank you!!

## License

MIT (c) 2018 TSUYUSATO "[MakeNowJust][]" Kitsune

<!-- Definitions -->

[katex]: https://katex.org/
[remark]: https://remark.js.org/
[unified]: https://unified.js.org/
[github-markdown-css]: https://github.com/sindresorhus/github-markdown-css/
[highlight.js]: https://highlightjs.org/
[gray-matter]: https://github.com/jonschlinkert/gray-matter
[babel]: https://babeljs.io/
[webpack]: https://webpack.js.org/
[jest]: https://jestjs.io/ja/
[maid]: https://github.com/egoist/maid
[makenowjust]: https://github.com/MakeNowJust/
[prettier]: https://prettier.io/
[raw]: https://raw.githubusercontent.com/MakeNowJust/md.html/gh-pages/index.html