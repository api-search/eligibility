---
api_specs:
- filename: norekey-api-openapi.json
  format: json
  label: NoRekey API API
  slug: norekey-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/norekey/openapi/_original/norekey-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use NoRekey for a business, our Data Processing Agreement applies to the statements you upload
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the service for any unlawful purpose, including money laundering or processing fraudulent documents
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
name: NoRekey
provenance_date: '2026-11-10'
provider_name: NoRekey
provider_slug: norekey
slug: norekey-eligibility
source_date: '2026-11-10'
source_filename: norekey-eligibility.yml
source_heading: Eligibility
source_page: https://norekey.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NoRekey\naid: norekey\nurl: https://norekey.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use NoRekey for a business, our Data Processing Agreement applies to the statements you upload\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: use the service for any unlawful purpose, including money laundering or processing fraudulent documents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/norekey/eligibility/norekey-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from NoRekey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Data Conversion
- Software-as-a-Service
- Banking
---
