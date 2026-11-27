---
api_specs:
- filename: reodev-openapi-generated.yml
  format: yaml
  label: Reo.dev API
  slug: reodev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reodev/openapi/_ae-authored/reodev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended solely for business and professional use.
    type: business
  minimum_age:
    text: you confirm that you are acting in a business or professional capacity, are of legal age, and are legally competent to enter into a binding agreement.
    value: legal age
  restricted_uses:
  - summary: Evaluation access limits
    text: Evaluation Access may not be used for production, commercial, revenue-generating or operational purposes
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
name: Reo.dev
provenance_date: '2026-11-10'
provider_name: Reo.dev
provider_slug: reodev
slug: reodev-eligibility
source_date: '2026-11-10'
source_filename: reodev-eligibility.yml
source_heading: Eligibility
source_page: https://www.reo.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reo.dev\naid: reodev\nurl: https://www.reo.dev/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended solely for business and professional use.\nrestricted_uses:\n- summary: Evaluation access limits\n  text: Evaluation Access may not be used for production, commercial, revenue-generating or operational purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you confirm that you are acting in a business or professional capacity,\
  \ are of legal age, and are legally\n    competent to enter into a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/reodev/eligibility/reodev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Reo.dev's own page on 2026-11-10.
synthetic: false
tags:
- Low-Code
- API Platform
- Integration
- Developer Tools
- Startups
---
