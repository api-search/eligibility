---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Personal accounts Vivid Money S.A. General Terms and Conditions
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited business activities
    text: Prohibited Business Activities PDF
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
name: Vivid
provenance_date: '2026-11-10'
provider_name: Vivid
provider_slug: vivid
slug: vivid-eligibility
source_date: '2026-11-10'
source_filename: vivid-eligibility.yml
source_heading: Eligibility
source_page: https://vivid.money/en-eu/legal-documents/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vivid\naid: vivid\nurl: https://vivid.money/en-eu/legal-documents/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Personal accounts Vivid Money S.A. General Terms and Conditions\nrestricted_uses:\n- summary: Prohibited business activities\n  text: Prohibited Business Activities PDF\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vivid/eligibility/vivid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Vivid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Neobank
- Payments
- Open Banking
- Investment
- Europe
---
