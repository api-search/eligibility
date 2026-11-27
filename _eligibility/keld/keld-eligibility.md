---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a contract.
    type: individual
  - text: If you accept on behalf of an organization, you confirm you're authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a contract.
    value: '18'
  restricted_uses:
  - summary: Decisions with legal, medical, financial or safety consequences
    text: Don't use output as the sole basis for decisions with legal, medical, financial or safety consequences.
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
name: Keld
provenance_date: '2026-11-09'
provider_name: Keld
provider_slug: keld
slug: keld-eligibility
source_date: '2026-11-09'
source_filename: keld-eligibility.yml
source_heading: Eligibility
source_page: https://keld.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keld\naid: keld\nurl: https://keld.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a contract.\n- type: business\n  text: If you accept on behalf of an organization, you confirm you're authorized to bind it.\nrestricted_uses:\n- summary: Decisions with legal, medical, financial or safety consequences\n  text: Don't use output as the sole basis for decisions with legal, medical, financial or safety consequences.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a contract.\n"
source_yaml_url: https://artifacts.apis.io/keld/eligibility/keld-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Keld's own page on 2026-11-09.
synthetic: false
tags:
- Inference
- Marketplace
- Model Marketplace
- Enterprise AI
---
