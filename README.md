# claude-plugins

Michael Jerris's Claude Code plugin marketplace.

```sh

claude plugin marketplace add mjerris/claude-plugins
claude plugin install scout@mjerris
```

| Plugin | What it is |
|---|---|
| [scout](https://github.com/mjerris/scout) | An always-on helper on your Mac for Claude: local voice, Mac tools, mail and calendar, with spoken approvals. Sets up its own background app. |

Each plugin lives in its own repo; this one only lists them. To add one, add an
entry to `.claude-plugin/marketplace.json` and run `claude plugin validate .`.
