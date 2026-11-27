---
api_specs:
- filename: anahana-com-discovery-api-openapi.yml
  format: yaml
  label: Anahana Discovery API
  slug: anahana-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-discovery-api-openapi.yml
- filename: anahana-com-mcp-api-openapi.yml
  format: yaml
  label: Anahana MCP API
  slug: anahana-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-mcp-api-openapi.yml
- filename: anahana-com-oauth-api-openapi.yml
  format: yaml
  label: Anahana OAuth API
  slug: anahana-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-oauth-api-openapi.yml
claim_count: 1
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
  - summary: Medical reliance
    text: The content on this website is for informational purposes only and is not intended as medical advice, diagnosis, or treatment.
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
name: Anahana
provenance_date: '2026-11-09'
provider_name: Anahana
provider_slug: anahana-com
slug: anahana-com-eligibility
source_date: '2026-11-09'
source_filename: anahana-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.anahana.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anahana\naid: anahana-com\nurl: https://www.anahana.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Medical reliance\n  text: The content on this website is for informational purposes only and is not intended as medical advice, diagnosis,\n    or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anahana-com/eligibility/anahana-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Anahana's own page on 2026-11-09.
synthetic: false
tags:
- SpiritualWellness
- Personal Growth
- Astrology
- Meditation
- Yoga
---
