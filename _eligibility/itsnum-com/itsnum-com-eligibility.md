---
api_specs:
- filename: itsnum-com-agent-api-openapi.yml
  format: yaml
  label: itsnum-com Agent API
  slug: itsnum-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsnum-com/openapi/itsnum-com-agent-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By messaging NUM or using the site, you agree to these terms.
    type: individual
  - text: Listing and claiming a business on NUM is free.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fair use restrictions
    text: Don't use NUM to break the law, harass anyone, send spam, attempt to extract our data or systems (including scraping, prompt-injection, or reverse engineering), or make fraudulent bookings.
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
name: itsnum-com
provenance_date: '2026-11-09'
provider_name: itsnum-com
provider_slug: itsnum-com
slug: itsnum-com-eligibility
source_date: '2026-11-09'
source_filename: itsnum-com-eligibility.yml
source_heading: Eligibility
source_page: https://itsnum.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: itsnum-com\naid: itsnum-com\nurl: https://itsnum.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By messaging NUM or using the site, you agree to these terms.\n- type: business\n  text: Listing and claiming a business on NUM is free.\nrestricted_uses:\n- summary: Fair use restrictions\n  text: Don't use NUM to break the law, harass anyone, send spam, attempt to extract our data or systems (including\n    scraping, prompt-injection, or reverse engineering), or make fraudulent bookings.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/itsnum-com/eligibility/itsnum-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from itsnum-com's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- eSIM
- Telecommunications
- Marketplace
- Company
---
