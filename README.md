# marp-themes
Themes for **[Marp for VS Code](https://github.com/marp-team/marp-vscode)**.


## Usage
1. Set the URL of the theme CSS file in `.vscode/settings.json`:

```json
{
  "markdown.marp.themes": [
    "https://raw.githubusercontent.com/taznica/marp-themes/master/themes/irodori.css"
  ]
}
```

Or you can use the path to the downloaded file. Set the relative path from your workspace folder:

```json
{
  "markdown.marp.themes": [
    "/relative/path/to/irodori.css"
  ]
}
```


2. Specify the theme name in your markdown file:

```yml
---

marp: true
theme: irodori

---
```


## Themes
### irodori

```yml
theme: irodori
class:
- (default)
- invert
- title
- title-invert

- blue
- invert-blue
- title-blue
- title-invert-blue

- green
- invert-green
- title-green
- title-invert-green

- orange
- invert-orange
- title-orange
- title-invert-orange

- pink
- invert-pink
- title-pink
- title-invert-pink

```