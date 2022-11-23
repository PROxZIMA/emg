# emg

https://emg.proxzima.dev/

A fork of [emgithub](https://github.com/yusanshi/emgithub) with some extra tweaks.
- PDF support using [pdf.js](https://mozilla.github.io/pdf.js/).
- Styles ids can be automated using javascript.

```js
// https://highlightjs.org/static/demo/
// Run the following in browser console and paste the result in the 404.html file
let styles = {};
[...document.getElementsByTagName('link')].forEach(link => {
  if (link.href.startsWith('https://highlightjs.org/static/demo/styles/')) {
    data[link.href.slice(43, -4)] = link.title;
  }
})
copy(styles);
```

## Credits

- [Highlight.js](https://github.com/highlightjs/highlight.js/) - Javascript syntax highlighter.
- [highlightjs-line-numbers.js](https://github.com/wcoder/highlightjs-line-numbers.js) - Highlight.js line numbers plugin.
- [marked](https://github.com/markedjs/marked) - Markdown parser.
- [github-markdown-css](https://github.com/sindresorhus/github-markdown-css) - GitHub Markdown style.
- [notebookjs](https://github.com/jsvine/notebookjs) - Jupyter/IPython notebooks render.
- [pdf.js](https://mozilla.github.io/pdf.js/) - Parsing and rendering PDFs.
- [Loading.io](https://loading.io/) - Loading animation.
- [GitHub Corners](https://github.com/tholman/github-corners).
- Icons made by [Vectors Market](https://www.flaticon.com/authors/vectors-market) and [Dave Gandy](https://www.flaticon.com/authors/dave-gandy) from [www.flaticon.com](https://www.flaticon.com/).
