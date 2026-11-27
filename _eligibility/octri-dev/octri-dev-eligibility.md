---
api_specs:
- filename: octri-dev-openapi-generated.yml
  format: yaml
  label: Octri API
  slug: octri-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octri-dev/openapi/_ae-authored/octri-dev-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to hold an account.
    type: individual
  - text: If you accept on behalf of a company, you confirm you are authorised to bind it, and “you” means that company.
    type: business
  minimum_age:
    text: You must be at least 16 years old to hold an account.
    value: '16'
  restricted_uses:
  - summary: No account sharing
    text: You may not share one account between several people, or resell access to the dashboard as if it were your own product.
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
name: Octri
provenance_date: '2026-11-10'
provider_name: Octri
provider_slug: octri-dev
slug: octri-dev-eligibility
source_date: '2026-11-10'
source_filename: octri-dev-eligibility.yml
source_heading: Eligibility
source_page: https://octri.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Octri\naid: octri-dev\nurl: https://octri.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to hold an account.\n- type: business\n  text: If you accept on behalf of a company, you confirm you are authorised to bind it, and “you” means that company.\nrestricted_uses:\n- summary: No account sharing\n  text: You may not share one account between several people, or resell access to the dashboard as if it were your\n    own product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/octri-dev/eligibility/octri-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Octri's own page on 2026-11-10.
synthetic: false
tags:
- Company
- OpenAPI
- Documentation
- SDK
- Monitoring
- MCP
- API Tooling
- API Documentation
- SDK Generation
- API Monitoring
- SDK Monitoring
---
