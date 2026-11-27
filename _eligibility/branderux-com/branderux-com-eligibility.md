---
api_specs:
- filename: branderux-com-openapi-generated.yml
  format: yaml
  label: BranderUX API
  slug: branderux-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branderux-com/openapi/_ae-authored/branderux-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You" means the business or person with a BranderUX account.'
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Safety-critical, medical or emergency uses
    text: The Service is not designed for uses where a failure could cause injury, loss of life or serious loss you cannot reverse (safety-critical, medical or emergency uses)
  - summary: Advice only a licensed professional may give
    text: or for uses where the assistant itself gives advice that only a licensed professional may give
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
name: BranderUX
provenance_date: '2026-11-09'
provider_name: BranderUX
provider_slug: branderux-com
slug: branderux-com-eligibility
source_date: '2026-11-09'
source_filename: branderux-com-eligibility.yml
source_heading: Eligibility
source_page: https://branderux.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BranderUX\naid: branderux-com\nurl: https://branderux.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"You\" means the business or person with a BranderUX account.'\nrestricted_uses:\n- summary: Safety-critical, medical or emergency uses\n  text: The Service is not designed for uses where a failure could cause injury, loss of life or serious loss you\n    cannot reverse (safety-critical, medical or emergency uses)\n- summary: Advice only a licensed professional may give\n  text: or for uses where the assistant itself\
  \ gives advice that only a licensed professional may give\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/branderux-com/eligibility/branderux-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BranderUX's own page on 2026-11-09.
synthetic: false
tags:
- AI App Builder
- Agentic applications
- MCP app
- Dashboards
---
