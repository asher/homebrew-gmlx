# asher/gmlx

The Homebrew tap for [gmlx](https://github.com/asher/gmlx), a local inference
platform for Apple Silicon. It needs macOS 26.2 or newer.

```sh
brew install asher/gmlx/gmlx
brew upgrade gmlx
```

The formula installs gmlx with every extra into its own virtual environment,
with each dependency pinned to the versions released together. The gmlx
release workflow generates `Formula/gmlx.rb` with `scripts/brew_formula.py`
and pushes it here after it installs and tests cleanly, so do not edit the
formula by hand.
