# FactoryFox plugins

[FactoryFox](https://getfactoryfox.com/) is a directory of industrial suppliers where every fact keeps its source. This repository is a plugin marketplace with one plugin, **factoryfox**: a supplier-sourcing skill plus the public FactoryFox MCP server (https://getfactoryfox.com/api/mcp). The tools are read-only, need no account and only return public data.

## Install

```bash
claude plugin marketplace add monemetrics/factoryfox-plugins
claude plugin install factoryfox@factoryfox
```

In claude.ai, the Claude desktop app or Cowork: Customize > Plugins > Add > Add marketplace, then enter `monemetrics/factoryfox-plugins`. Other hosts (Codex, ChatGPT, any MCP client) are covered in [factoryfox/README.md](factoryfox/README.md).

Then ask, for example: "Find suppliers for low-volume PCB assembly in Europe and show the evidence."

## Tools

- `search_suppliers`: Search suppliers
- `find_company`: Find a company
- `get_company_profile`: Get supplier profile
- `browse_suppliers`: Browse supplier directory
- `list_supplier_taxonomy`: List supplier taxonomy

[Privacy policy](https://getfactoryfox.com/privacy) · [Terms](https://getfactoryfox.com/terms) · privacy@getfactoryfox.com

This repository is published automatically from the FactoryFox source; open issues here or email us.
