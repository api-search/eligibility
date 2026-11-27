---
api_specs:
- filename: metadata-health-api-openapi.yml
  format: yaml
  label: Metadata Health API
  slug: metadata-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metadata/openapi/metadata-health-api-openapi.yml
- filename: metadata-mcp-api-openapi.yml
  format: yaml
  label: Metadata MCP API
  slug: metadata-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metadata/openapi/metadata-mcp-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You," "your," or "Customer" means the person or entity using or receiving the Company Services'
    type: business
  minimum_age:
    text: Authorized Users must be 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Supplementary Data restricted uses
    text: (vi) for any purpose other than business-to-business marketing activities
  - summary: No sensitive information
    text: YOU AGREE NOT TO USE THE COMPANY SERVICES TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Metadata
provenance_date: '2026-11-10'
provider_name: Metadata
provider_slug: metadata
slug: metadata-eligibility
source_date: '2026-11-10'
source_filename: metadata-eligibility.yml
source_heading: Eligibility
source_page: https://metadata.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metadata\naid: metadata\nurl: https://metadata.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"You,\" \"your,\" or \"Customer\" means the person or entity using or receiving the Company Services'\nrestricted_uses:\n- summary: Supplementary Data restricted uses\n  text: (vi) for any purpose other than business-to-business marketing activities\n- summary: No sensitive information\n  text: YOU AGREE NOT TO USE THE COMPANY SERVICES TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Authorized Users must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/metadata/eligibility/metadata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Metadata's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Marketing Automation
- Demand Generation
- Advertising
- B2B
- Artificial Intelligence
- MCP
- AI Agents
- Paid Media
- Account Based Marketing
---
