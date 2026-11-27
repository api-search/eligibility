---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - UG
    text: you, a resident of Uganda
  entity_types:
  - text: The Services offered by Asaak can only be utilized by persons over the age of 18.
    type: individual
  minimum_age:
    text: persons over the age of 18
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the App for domestic and private use. You agree not to use the App and Documents for any commercial, business or resale purposes
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
name: Asaak
provenance_date: '2026-11-09'
provider_name: Asaak
provider_slug: asaak
slug: asaak-eligibility
source_date: '2026-11-09'
source_filename: asaak-eligibility.yml
source_heading: Eligibility
source_page: https://api.asaak.net/v0/app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asaak\naid: asaak\nurl: https://api.asaak.net/v0/app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - UG\n  excluded: []\n  text: you, a resident of Uganda\nentity_types:\n- type: individual\n  text: The Services offered by Asaak can only be utilized by persons over the age of 18.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We only supply the App for domestic and private use. You agree not to use the App and Documents for any\n    commercial, business or resale purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: persons over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/asaak/eligibility/asaak-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Asaak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Asset Financing
- Financial Services
- Working Capital
- Africa
- Uganda
- Mobility
---
