# `dracula` theme for Rune

a theme pkg for [Rune](https://rune.build) containing the [Dracula](https://draculatheme.com) palette, built from the official [color spec](https://draculatheme.com/spec).

<img width="1264" height="1388" alt="screenshot" src="https://github.com/user-attachments/assets/d30d4a89-2186-4115-b5cc-38e9b36717ea" />

## Install

> requires rune built from `main` at commit `e428893` (2026-10-04) or later.

In the Rune console, run:

```text
pkg install github.com/quietdreamr/rune-theme-dracula
```

From the command prompt you can do the same in one step:

```text
console pkg install github.com/quietdreamr/rune-theme-dracula
```

Then activate the theme:

```text
guitheme dracula
```

To use it at startup, set the following in your own `config.yaml`:

```yaml
gui:
  default_theme: dracula
```
