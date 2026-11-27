---
api_specs:
- filename: anew-a2a-api-openapi.yml
  format: yaml
  label: anew A2a API
  slug: anew-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anew/openapi/anew-a2a-api-openapi.yml
- filename: anew-mcp-api-openapi.yml
  format: yaml
  label: anew MCP API
  slug: anew-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anew/openapi/anew-mcp-api-openapi.yml
- filename: anew-pages-api-openapi.yml
  format: yaml
  label: anew Pages API
  slug: anew-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anew/openapi/anew-pages-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use and abuse
    text: unlawful use and abuse are prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: There is no account, no cookie, and no profile
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: anew
provenance_date: '2026-11-09'
provider_name: anew
provider_slug: anew
slug: anew-eligibility
source_date: '2026-11-09'
source_filename: anew-eligibility.yml
source_heading: Eligibility
source_page: https://github.com/round/anew.page/blob/main/LICENSE.md#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: anew\naid: anew\nurl: https://github.com/round/anew.page/blob/main/LICENSE.md#terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use and abuse\n  text: unlawful use and abuse are prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: There is no account, no cookie, and no profile\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anew/eligibility/anew-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from anew's own page on 2026-11-09.
synthetic: false
tags:
- HTML
- Webpage
- Websites
- URLs
- Encode
- Share
- Web Publishing
- Developer Tools
- MCP
- A2A
- AI / Agent Tooling
- Llms.txt
- Agents.txt
- Agent Skills
- WebMCP
- OpenAPI
- stateless
- Immutable
- No Auth
- Static Sites
- url-encoding
---
