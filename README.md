# mi-subbotin/homebrew-tap

Homebrew tap for [`lazyagent`](https://github.com/mi-subbotin/lazyagent) and any future tools I publish.

## Install

```bash
brew install mi-subbotin/tap/lazyagent
```

`brew tap mi-subbotin/tap` happens automatically on first install — there's no separate `tap` step.

> **macOS Gatekeeper**: the released binary is not yet notarized. If macOS refuses to launch it, run:
> ```bash
> xattr -d com.apple.quarantine "$(which lazyagent)"
> ```
> Notarization is on the lazyagent roadmap.

## Updates

The formula in [`Formula/lazyagent.rb`](Formula/lazyagent.rb) is auto-updated by [GoReleaser](https://goreleaser.com) on every `v*` tag push to the lazyagent repo — there's no manual bump-formula-pr workflow.

## Tools in this tap

| Formula     | Source repo                                                | Description                                                                                                  |
| ----------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `lazyagent` | [mi-subbotin/lazyagent](https://github.com/mi-subbotin/lazyagent) | Lazygit-style TUI for skills, subagents, MCP servers, prompts and memory across Claude Code, Codex and Gemini CLI |

## License

Each tool in this tap retains its own license; see the linked source repository for details. The formulas themselves are released under the [Unlicense](https://unlicense.org/) — copy and adapt freely.
