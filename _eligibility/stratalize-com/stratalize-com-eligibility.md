---
api_specs:
- filename: stratalize-com-x402-api-openapi.yml
  format: yaml
  label: stratalize-com X402 API
  slug: stratalize-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stratalize-com/openapi/stratalize-com-x402-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ACCEPTING ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE AUTHORITY TO BIND THAT ORGANIZATION.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use in violation of law
    text: Use the Platform in violation of applicable law, regulation, or these Terms
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
name: stratalize-com
provenance_date: '2026-11-10'
provider_name: stratalize-com
provider_slug: stratalize-com
slug: stratalize-com-eligibility
source_date: '2026-11-10'
source_filename: stratalize-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.stratalize.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: stratalize-com\naid: stratalize-com\nurl: https://www.stratalize.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ACCEPTING ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE AUTHORITY TO BIND THAT ORGANIZATION.\nrestricted_uses:\n- summary: No use in violation of law\n  text: Use the Platform in violation of applicable law, regulation, or these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stratalize-com/eligibility/stratalize-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from stratalize-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Project Controls
- Schedule Management
- Artificial Intelligence
- Compliance
---
