---
api_specs:
- filename: australiawidefirstaid-com-agent-api-openapi.yml
  format: yaml
  label: Australia Wide First Aid Agent API
  slug: australia-wide-first-aid-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/australiawidefirstaid-com/openapi/australiawidefirstaid-com-agent-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This document establishes the mutual obligations between Australia Wide First Aid and every student, employer, or organisation engaging with our Registered Training Organisation (RTO).
    type: individual
  - text: every student, employer, or organisation engaging with our Registered Training Organisation (RTO)
    type: business
  minimum_age:
    text: null
    value: null
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
name: australiawidefirstaid-com
provenance_date: '2026-11-09'
provider_name: australiawidefirstaid-com
provider_slug: australiawidefirstaid-com
slug: australiawidefirstaid-com-eligibility
source_date: '2026-11-09'
source_filename: australiawidefirstaid-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.australiawidefirstaid.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: australiawidefirstaid-com\naid: australiawidefirstaid-com\nurl: https://www.australiawidefirstaid.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This document establishes the mutual obligations between Australia Wide First Aid and every student, employer,\n    or organisation engaging with our Registered Training Organisation (RTO).\n- type: business\n  text: every student, employer, or organisation engaging with our Registered Training Organisation (RTO)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/australiawidefirstaid-com/eligibility/australiawidefirstaid-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from australiawidefirstaid-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- First Aid
- Training
- Australia
- Health
---
