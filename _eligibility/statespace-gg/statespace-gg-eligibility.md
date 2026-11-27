---
api_specs:
- filename: statespace-gg-openapi-generated.yml
  format: yaml
  label: Statespace API
  slug: statespace-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statespace-gg/openapi/_ae-authored/statespace-gg-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to enter an agreement.
    type: individual
  - text: If you use the service for an organization, you must have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter an agreement.
    value: '18'
  restricted_uses:
  - summary: Life-safety uses
    text: Do not use the service where a failure could cause death, serious injury, or significant physical harm.
  - summary: Regulated sensitive data
    text: Do not submit passwords, payment card details, health records, or other regulated sensitive data unless a separate written agreement expressly permits that use and sets the required safeguards.
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
name: Statespace
provenance_date: '2026-11-10'
provider_name: Statespace
provider_slug: statespace-gg
slug: statespace-gg-eligibility
source_date: '2026-11-10'
source_filename: statespace-gg-eligibility.yml
source_heading: Eligibility
source_page: https://statespace.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Statespace\naid: statespace-gg\nurl: https://statespace.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter an agreement.\n- type: business\n  text: If you use the service for an organization, you must have authority to bind that organization.\nrestricted_uses:\n- summary: Life-safety uses\n  text: Do not use the service where a failure could cause death, serious injury, or significant physical harm.\n- summary: Regulated sensitive data\n  text: Do not submit passwords, payment\
  \ card details, health records, or other regulated sensitive data unless\n    a separate written agreement expressly permits that use and sets the required safeguards.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter an agreement.\n"
source_yaml_url: https://artifacts.apis.io/statespace-gg/eligibility/statespace-gg-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Statespace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Simulation
- Analytics
- Cloud
- Engineering
---
