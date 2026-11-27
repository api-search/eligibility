---
api_specs:
- filename: catalystedgescanner-com-openapi-generated.yml
  format: yaml
  label: Catalyst Edge API
  slug: catalystedgescanner-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catalystedgescanner-com/openapi/_ae-authored/catalystedgescanner-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 18 years or older to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Use the service to violate any law in your jurisdiction or ours.
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
name: Catalyst Edge
provenance_date: '2026-11-09'
provider_name: Catalyst Edge
provider_slug: catalystedgescanner-com
slug: catalystedgescanner-com-eligibility
source_date: '2026-11-09'
source_filename: catalystedgescanner-com-eligibility.yml
source_heading: Eligibility
source_page: https://catalystedgescanner.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Catalyst Edge\naid: catalystedgescanner-com\nurl: https://catalystedgescanner.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the service to violate any law in your jurisdiction or ours.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to create an account.\n"
source_yaml_url: https://artifacts.apis.io/catalystedgescanner-com/eligibility/catalystedgescanner-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Catalyst Edge's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- SEC
- Market Data
- Analytics
- Platform
---
