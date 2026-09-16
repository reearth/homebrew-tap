# Re:Earth Homebrew tap

Homebrew formulae for [Re:Earth](https://github.com/reearth) command-line
tools, on macOS and Linux, Apple silicon and x86_64.

```sh
brew tap reearth/tap
brew install ezu
```

Or in one step, without tapping first:

```sh
brew install reearth/tap/ezu
```

## Formulae

| Formula | What it is |
|---|---|
| `ezu` | [reearth/ezu](https://github.com/reearth/ezu) — a command-line renderer for the Ezu Style Spec |

Each formula installs a prebuilt binary from the tool's own GitHub release,
so `brew install` needs no compiler and no language toolchain.

## How these are updated

Nothing here is edited by hand. Each tool's release workflow regenerates its
formula from the archives it is about to publish — the checksums describe the
very bytes that release attached — and pushes the result here. A formula's
first line names the script that wrote it.

To add a tool, have its release workflow write `Formula/<name>.rb` to this
repository, and add a row to the table above.
