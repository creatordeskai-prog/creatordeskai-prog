# Creator Desk AI — Machine Products

Creator Desk Agent Supervisor exposes nine bounded machine-callable utilities.

Public origin:
https://creator-desk-agent-supervisor.onrender.com

API docs:
https://creator-desk-agent-supervisor.onrender.com/docs

OpenAPI:
https://creator-desk-agent-supervisor.onrender.com/openapi.json

Machine discovery:
https://creator-desk-agent-supervisor.onrender.com/.well-known/creator-desk-agent-supervisor.json

MCP endpoint:
https://creator-desk-agent-supervisor.onrender.com/mcp

## Products

| # | Product | Endpoint | Default price |
|---|---|---|---:|
| 1 | Commerce Completion Verify | `POST /v1/commerce/readiness` | $0.05 |
| 2 | Public URL / Deployment Inspector | `POST /v1/url/inspect` | $0.005 |
| 3 | Structured Web Page Extractor | `POST /v1/web/extract` | $0.005 |
| 4 | Page Evidence Checker | `POST /v1/web/evidence` | $0.005 |
| 5 | Crawl Config / Sitemap Discovery | `POST /v1/site/crawl-config` | $0.002 |
| 6 | JSON Field Extractor | `POST /v1/json/extract` | $0.003 |
| 7 | Format Converter | `POST /v1/data/convert` | $0.003 |
| 8 | DNS Lookup | `POST /v1/dns/lookup` | $0.002 |
| 9 | JSON Contract Validator | `POST /v1/json/validate` | $0.001 |

Product #1 is also exposed through MCP as the paid tool `creator_desk_verify_completion`.

## Agent use cases

These narrow operations can help another system:

- inspect a public deployment
- extract structured information from a bounded public page
- check whether expected evidence is present
- discover crawl configuration or sitemaps
- pull fields from JSON
- convert bounded tabular formats
- resolve public DNS records
- validate JSON against a documented bounded contract
- evaluate submitted commerce-completion evidence

## Traction truth

At the most recent verified Creator Desk checkpoint on September 25, 2026:

- verified machine-product customers: **0**
- verified successful paid calls: **0**
- verified machine-product revenue: **$0**

Those numbers change only from external evidence.

> **AUTOMATION IS NOT COMPLETION. VERIFICATION IS COMPLETION.**
