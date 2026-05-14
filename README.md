# Basel III + AI Model Risk Management MCP

[![PyPI](https://img.shields.io/pypi/v/basel-ai-overlay-mcp)](https://pypi.org/project/basel-ai-overlay-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

Basel III + SR 11-7 + ECB TRIM AI/ML model risk management for banks deploying AI in credit, capital, treasury, AML/CFT.

## Install

```bash
pip install basel-ai-overlay-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `model_risk_tier` | Tier AI/ML models per SR 11-7 materiality framework |
| `validation_requirements` | Independent model validation requirements + frequency |
| `ecb_trim_check` | ECB TRIM internal model investigation areas |
| `ifrs9_ecl_audit` | IFRS 9 Expected Credit Loss AI model governance |
| `frtb_market_risk` | FRTB internal model approach AI/ML usage check |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/basel-ai-overlay-mcp -->
