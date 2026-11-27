---
api_specs:
- filename: meettempi-com-api-openapi.json
  format: json
  label: Tempi API API
  slug: tempi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meettempi-com/openapi/_original/meettempi-com-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 and use an email address you control.
    type: individual
  - text: If you create a team, you decide who joins it and what they can do.
    type: business
  minimum_age:
    text: You must be at least 16 and use an email address you control.
    value: '16'
  restricted_uses:
  - summary: Prohibited uses list
    text: 'Don’t use Tempi to: send spam, or book meetings with people who didn’t ask for them'
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
name: meettempi-com
provenance_date: '2026-11-10'
provider_name: meettempi-com
provider_slug: meettempi-com
slug: meettempi-com-eligibility
source_date: '2026-11-10'
source_filename: meettempi-com-eligibility.yml
source_heading: Eligibility
source_page: https://meettempi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: meettempi-com\naid: meettempi-com\nurl: https://meettempi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 and use an email address you control.\n- type: business\n  text: If you create a team, you decide who joins it and what they can do.\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'Don’t use Tempi to: send spam, or book meetings with people who didn’t ask for them'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ You must be at least 16 and use an email address you control.\n"
source_yaml_url: https://artifacts.apis.io/meettempi-com/eligibility/meettempi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from meettempi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Artificial Intelligence
- Calendar
- Collaboration
---
