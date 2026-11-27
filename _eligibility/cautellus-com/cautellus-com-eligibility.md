---
api_specs:
- filename: cautellus-com-openapi-generated.yml
  format: yaml
  label: Cautellus API
  slug: cautellus-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cautellus-com/openapi/_ae-authored/cautellus-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for the internal security work of a single business or organization that you own or are employed by
    type: business
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Acceptable Use Policy
    text: We reserve the right to refuse service and terminate accounts that violate this policy.
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
name: Cautellus
provenance_date: '2026-11-09'
provider_name: Cautellus
provider_slug: cautellus-com
slug: cautellus-com-eligibility
source_date: '2026-11-09'
source_filename: cautellus-com-eligibility.yml
source_heading: Eligibility
source_page: https://cautellus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cautellus\naid: cautellus-com\nurl: https://cautellus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for the internal security work of a single business or organization that you own or are employed by\nrestricted_uses:\n- summary: Acceptable Use Policy\n  text: We reserve the right to refuse service and terminate accounts that violate this policy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you\
  \ are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/cautellus-com/eligibility/cautellus-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cautellus's own page on 2026-11-09.
synthetic: false
tags:
- Scam Detection
- Artificial Intelligence
- Cybersecurity
- Consumer Protection
- Chrome Extension
- Company
---
