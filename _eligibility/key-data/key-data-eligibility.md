---
api_specs:
- filename: key-data-openapi-generated.yml
  format: yaml
  label: Key Data API
  slug: key-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/key-data/openapi/_ae-authored/key-data-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For Enterprise or DMO customers who have executed a separate written licensing agreement, the negotiated agreement controls in the event of conflict
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competing analytics product
    text: Use the Services to develop, train, or enhance any competing analytics, benchmarking, or data product.
  - summary: No unlawful activity
    text: may not use the Services or Key Data output in furtherance of unlawful activity.
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
name: Key Data
provenance_date: '2026-11-09'
provider_name: Key Data
provider_slug: key-data
slug: key-data-eligibility
source_date: '2026-11-09'
source_filename: key-data-eligibility.yml
source_heading: Eligibility
source_page: https://www.keydata.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Key Data\naid: key-data\nurl: https://www.keydata.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For Enterprise or DMO customers who have executed a separate written licensing agreement, the negotiated\n    agreement controls in the event of conflict\nrestricted_uses:\n- summary: No competing analytics product\n  text: Use the Services to develop, train, or enhance any competing analytics, benchmarking, or data product.\n- summary: No unlawful activity\n  text: may not use the Services or Key Data output in furtherance of unlawful\
  \ activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/key-data/eligibility/key-data-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Key Data's own page on 2026-11-09.
synthetic: false
tags:
- Short-Term Rental
- Real-Time Data
- Analytics
- Property Management
- Vacation Rentals
---
