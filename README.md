# homebrew-icuvisor

Homebrew tap for [icuvisor](https://github.com/ricardocabral/icuvisor), an open-source MCP server that connects [intervals.icu](https://intervals.icu) training data to AI assistants.

## Install

```sh
brew install ricardocabral/icuvisor/icuvisor
```

Or, equivalently:

```sh
brew tap ricardocabral/icuvisor
brew install icuvisor
```

After installing, run `icuvisor setup` once to store your intervals.icu API key in the system keychain, then point your MCP client at `icuvisor serve`. See the [main project README](https://github.com/ricardocabral/icuvisor#readme) for client setup guides.

## Updating

```sh
brew update
brew upgrade icuvisor
```

## How this tap is maintained

The `Formula/icuvisor.rb` file is generated automatically by [GoReleaser](https://goreleaser.com) on every tagged release of [`ricardocabral/icuvisor`](https://github.com/ricardocabral/icuvisor). Do not edit the formula by hand — changes will be overwritten on the next release. Open issues against the main project repository, not this tap.

## License

MIT — see [LICENSE](LICENSE).
