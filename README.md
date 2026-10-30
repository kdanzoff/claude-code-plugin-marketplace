# claude-code-plugin-marketplace

A Claude Code marketplace by KDANZ. Each plugin lives in its own repository; this repository only lists them in `.claude-plugin/marketplace.json`.

## Install

Add the marketplace, then install a plugin from it:

```
/plugin marketplace add kdanzoff/claude-code-plugin-marketplace
/plugin install statusline@kdanzoff
```

## Plugins

| Plugin | What it does | Repository |
| --- | --- | --- |
| `statusline` | A band above the prompt showing the folder, git branch, model and a gauge of the context window in use. | [kdanzoff/statusline-claude-code-plugin](https://github.com/kdanzoff/statusline-claude-code-plugin) |

## Adding a plugin

Give the plugin its own repository, then add an entry to `.claude-plugin/marketplace.json` with a `github` source pointing at it, and run `claude plugin validate .`.
