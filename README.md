## Setup

```bash
open inline-static.html
```

There's only a two files.

`styles.css`
Simple styling for the app.

`inline-static.html`
A HTML page with no JS at all. There's two structures, the first is a `<p>` followed
by a `<button>`. The second is the same but there's a `<textarea>` in the `<p>`.

## The Challenge

Using CSS, make the text in the `<textarea>` the same width as the text in the `<p>`.
The `<button>` should still be inline beside the text. On narrow browsers (roughly
400px wide), the `<button>` should flow under the text in the `<textarea>`.
