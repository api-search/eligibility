---
api_specs:
- filename: convertlyft-com-tools-api-openapi.yml
  format: yaml
  label: Convertlyft Tools API
  slug: convertlyft-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convertlyft-com/openapi/convertlyft-com-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other entity, you represent and warrant that you have authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: No sensitive personal data collection
    text: you will not configure the Tag, custom events, or server-side reporting to transmit to us any sensitive or special-category personal data
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
name: Convertlyft
provenance_date: '2026-11-09'
provider_name: Convertlyft
provider_slug: convertlyft-com
slug: convertlyft-com-eligibility
source_date: '2026-11-09'
source_filename: convertlyft-com-eligibility.yml
source_heading: Eligibility
source_page: https://convertlyft.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convertlyft\naid: convertlyft-com\nurl: https://convertlyft.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other entity, you represent and warrant that you have authority\n    to bind that entity\nrestricted_uses:\n- summary: No sensitive personal data collection\n  text: you will not configure the Tag, custom events, or server-side reporting to transmit to us any sensitive\n    or special-category personal data\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/convertlyft-com/eligibility/convertlyft-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Convertlyft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Analytics
- Conversion Rate Optimization
- Session Replay
- Heatmaps
- SEO
- Error Tracking
- MCP
---
