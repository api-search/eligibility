---
api_specs:
- filename: taxley-tools-api-openapi.yml
  format: yaml
  label: Taxley (UK Corporation Tax API) Tools API
  slug: taxley-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxley/openapi/taxley-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for small UK companies within the micro-entity (FRS 105) or small-company (FRS 102 §1A) regimes.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: No resale or third-party provision
    text: You must not resell or provide the Service to third parties except as a director or authorised person filing for your own company.
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
name: Taxley (UK Corporation Tax API)
provenance_date: '2026-11-10'
provider_name: Taxley (UK Corporation Tax API)
provider_slug: taxley
slug: taxley-eligibility
source_date: '2026-11-10'
source_filename: taxley-eligibility.yml
source_heading: Eligibility
source_page: https://taxley.co.uk/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Taxley (UK Corporation Tax API)\naid: taxley\nurl: https://taxley.co.uk/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for small UK companies within the micro-entity (FRS 105) or small-company (FRS 102\n    §1A) regimes.\nrestricted_uses:\n- summary: No resale or third-party provision\n  text: You must not resell or provide the Service to third parties except as a director or authorised person filing\n    for your own company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n \
  \ text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/taxley/eligibility/taxley-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Taxley (UK Corporation Tax API)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- United Kingdom
- Finance
---
