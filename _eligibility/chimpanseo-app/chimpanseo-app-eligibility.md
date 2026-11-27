---
api_specs:
- filename: chimpanseo-app-audit-api-openapi.yml
  format: yaml
  label: ChimpanSEO Audit API
  slug: chimpanseo-app-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chimpanseo-app/openapi/chimpanseo-app-audit-api-openapi.yml
- filename: chimpanseo-app-mcp-api-openapi.yml
  format: yaml
  label: ChimpanSEO MCP API
  slug: chimpanseo-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chimpanseo-app/openapi/chimpanseo-app-mcp-api-openapi.yml
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
  - summary: Prohibited content and conduct
    text: Generate illegal, defamatory, pornographic content or content that violates third-party rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service you must create an account with a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ChimpanSEO
provenance_date: '2026-11-09'
provider_name: ChimpanSEO
provider_slug: chimpanseo-app
slug: chimpanseo-app-eligibility
source_date: '2026-11-09'
source_filename: chimpanseo-app-eligibility.yml
source_heading: Eligibility
source_page: https://chimpanseo.app/legal/termini
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChimpanSEO\naid: chimpanseo-app\nurl: https://chimpanseo.app/legal/termini\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: Generate illegal, defamatory, pornographic content or content that violates third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service you must create an account with a valid email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chimpanseo-app/eligibility/chimpanseo-app-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ChimpanSEO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Generative Engine Optimization
- AI Content
- Content Marketing
- WordPress
- MCP
---
