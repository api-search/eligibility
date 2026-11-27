---
api_specs:
- filename: adona-robot-com-openapi-generated.yml
  format: yaml
  label: adona-robot-com API
  slug: adona-robot-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adona-robot-com/openapi/_ae-authored/adona-robot-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: to a company or a person acting for their business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not offered to consumers
    text: The service is not offered to consumers.
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
name: adona-robot-com
provenance_date: '2026-11-09'
provider_name: adona-robot-com
provider_slug: adona-robot-com
slug: adona-robot-com-eligibility
source_date: '2026-11-09'
source_filename: adona-robot-com-eligibility.yml
source_heading: Eligibility
source_page: https://adona-robot.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: adona-robot-com\naid: adona-robot-com\nurl: https://adona-robot.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: to a company or a person acting for their business\nrestricted_uses:\n- summary: Not offered to consumers\n  text: The service is not offered to consumers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adona-robot-com/eligibility/adona-robot-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from adona-robot-com's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Foreign Exchange
- Metals
- Swiss
---
