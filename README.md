# dependency-risk-notes

Summarize dependency updates and highlight likely upgrade risks.

## Run

Requires Node.js 20+.

```sh
npm start
```

The tool reads its development gateway settings from `config/local.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.
