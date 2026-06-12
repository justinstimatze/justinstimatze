# justinstimatze profile repo

## README.md formatting is intentional — do not strip the HTML

`README.md` is a GitHub profile page rendered as a JSON-shaped agent card. It uses raw HTML inside markdown:

- `<pre>` wrapper — preserves the JSON-like indentation and monospace rendering
- `<strong>` tags around keys — bold emphasis on JSON keys
- `<a href="...">name</a>` — clickable repo links throughout

**Do not strip these tags.** They are load-bearing for the rendering and the dozens of repo links it carries. Any "lint" pass that removes HTML to "normalize" the file is wrong for this repo.

If a post-edit hook or formatter strips the tags after a Write, treat that as a regression to fix, not an "intentional" change to preserve — restore the HTML and flag the strip mechanism.

## Line-length target

Lines render inside `<pre>` with no word-wrap. Cap rendered line length (HTML tags stripped, indentation kept) at **80 chars** so the README doesn't scroll off the edge on standard widths. Quick check:

```
python3 -c "import re; [print(len(re.sub(r'<[^>]+>','',l.rstrip())),l.rstrip()) for l in open('README.md')]" | sort -rn | head
```
