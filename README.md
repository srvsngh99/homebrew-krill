# homebrew-krillm

Homebrew tap for [KrillLM](https://github.com/srvsngh99/KrillLM) - fast local
LLM inference CLI for Apple Silicon.

## Install

```sh
brew tap srvsngh99/krillm
brew install krillm
```

## Update

```sh
brew update
brew upgrade krillm
```

## Requirements

Apple Silicon (M1 or newer), macOS.

## Quick start

```sh
krillm pull llama-3.2-3b
krillm run llama-3.2-3b

# Ollama / OpenAI compatible API server:
krillm serve --model llama-3.2-3b
```

The formula here tracks tagged releases of the main repo. The current
formula points at `v0.4.0`.
