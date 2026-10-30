# claude-code-plugin-marketplace

A Claude Code marketplace by KDANZ. Each plugin lives in its own repository; this repository only lists them in `.claude-plugin/marketplace.json`.

## Install

Add the marketplace, then install a plugin from it:

```
/plugin marketplace add kdanzoff/claude-code-plugin-marketplace
/plugin install topline@kdanzoff
```

## Plugins

| Plugin | What it does | Repository |
| --- | --- | --- |
| `topline` | top for Claude Code: a band above the prompt with the folder, git branch, model and effort, the context gauge, and the account's 5-hour and weekly limits, shared by every open session. | [kdanzoff/topline-claude-code-plugin](https://github.com/kdanzoff/topline-claude-code-plugin) |

## Adding a plugin

Give the plugin its own repository, then add an entry to `.claude-plugin/marketplace.json` with a `github` source pointing at it, and run `claude plugin validate .`.
