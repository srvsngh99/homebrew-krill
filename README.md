# homebrew-krill

Homebrew tap for [Krill](https://github.com/srvsngh99/Krill) - a local LLM
engine and coding agent in one Mac-native binary.

## Install

```sh
brew tap srvsngh99/krill
brew install krill
```

## Update

```sh
brew update
brew upgrade krill
```

## Requirements

Apple Silicon (M1 or newer), macOS 14 or newer. On macOS 15 and newer, brew
pours a prebuilt bottle. On macOS 14 it runs the install step instead, which
needs up-to-date Xcode Command Line Tools.

## Quick start

```sh
krill pull gemma-4-e2b
krill run gemma-4-e2b
krill code "fix the failing test"
krill serve
```

`.github/workflows/auto-bump.yml` keeps the formula on the latest Krill release
and builds its bottle.
