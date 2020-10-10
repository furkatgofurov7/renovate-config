# renovate-config
![Renovate banner](./renovate-banner.jpg)

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-green.svg)](https://github.com/RichardLitt/standard-readme)

> Shared [Renovate](https://renovatebot.com/) configuration for furkatgofurov7 repositories.

## Our Configuration

We have a custom set of rules for furkatgofurov7 repositories. We are generally...

* Letting Renovate decide how to [modify or update existing ranges](https://renovatebot.com/docs/configuration-options/#rangestrategy) on renovate enabled repos owned `dependencies`

* Grouping updates for our monorepos (such as [vscode](https://github.com/furkatgofurov7/vscode), [docker-curriculum](https://github.com/furkatgofurov7/docker-curriculum) and [awesome-README-templates](https://github.com/furkatgofurov7/awesome-README-templates)) into a single pull request.


## Usage

Reference the shared configuration in your repository's own `renovate.json` like so:

```json
{
  "extends": [
    "github>furkatgofurov7/renovate-config"
  ]
}
```

## Development

Our shared configuration is defined in [`default.json`](default.json).
