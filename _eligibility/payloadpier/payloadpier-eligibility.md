---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be authorized to use the submitted data and to make purchases for your account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful data or account misuse
    text: Do not access someone else's account, submit unlawful data, compromise the service, or bypass authorization or request limits.
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
name: PayloadPier
provenance_date: '2026-11-10'
provider_name: PayloadPier
provider_slug: payloadpier
slug: payloadpier-eligibility
source_date: '2026-11-10'
source_filename: payloadpier-eligibility.yml
source_heading: Eligibility
source_page: https://payloadpier.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayloadPier\naid: payloadpier\nurl: https://payloadpier.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be authorized to use the submitted data and to make purchases for your account.\nrestricted_uses:\n- summary: Unlawful data or account misuse\n  text: Do not access someone else's account, submit unlawful data, compromise the service, or bypass authorization\n    or request limits.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payloadpier/eligibility/payloadpier-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from PayloadPier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pricing
- SupplierComparison
- Data Processing
---
