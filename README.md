# Homebrew tap for twr

[twr](https://github.com/ignaval/twr) runs several coding agents from one conversation, in a
terminal UI or a desktop app.

```sh
brew install --cask ignaval/twr/twr   # the desktop app (Apple silicon); it updates itself
brew install ignaval/twr/twr          # the twr command; `brew upgrade` updates it
```

Each stable twr release updates this tap from its signed checksums
([release.yml](https://github.com/ignaval/twr/blob/main/.github/workflows/release.yml)).
Don't edit `Formula/` or `Casks/` here by hand: the next release overwrites them. Their
sources are in [release/homebrew](https://github.com/ignaval/twr/tree/main/release/homebrew).
