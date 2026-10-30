### [Rune](https://rune.build)

#### Install using Rune

> Requires Rune built from `main` at commit `e428893` (2026-10-04) or later.

In the Rune console, run:

```text
pkg install github.com/dracula/rune
```

From the command prompt you can do the same in one step:

```text
console pkg install github.com/dracula/rune
```

#### Install using Git

If you are a Git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/dracula/rune.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/rune/archive/main.zip) option and unzip it.

#### Activating theme

1. Install the package (see above).
2. Activate the theme:

```text
guitheme dracula
```

3. To use it at startup, set the following in your own `config.yaml`:

```yaml
gui:
  default_theme: dracula
```

4. Boom! It's working ✨
