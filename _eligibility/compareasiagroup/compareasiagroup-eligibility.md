---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the Services shall only be accessed and used directly by a private individual
    type: individual
  - text: or by a legal entity to find a product or service for that individual or entity on their own behalf
    type: business
  minimum_age:
    text: unless you are aged 18 and over
    value: '18'
  restricted_uses:
  - summary: AI Tools personal non-commercial only
    text: These AI Tools should be used for personal, lawful, non-commercial purposes only.
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
name: Compareasiagroup
provenance_date: '2026-11-09'
provider_name: Compareasiagroup
provider_slug: compareasiagroup
slug: compareasiagroup-eligibility
source_date: '2026-11-09'
source_filename: compareasiagroup-eligibility.yml
source_heading: Eligibility
source_page: https://www.moneyherogroup.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compareasiagroup\naid: compareasiagroup\nurl: https://www.moneyherogroup.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the Services shall only be accessed and used directly by a private individual\n- type: business\n  text: or by a legal entity to find a product or service for that individual or entity on their own behalf\nrestricted_uses:\n- summary: AI Tools personal non-commercial only\n  text: These AI Tools should be used for personal, lawful, non-commercial purposes only.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: unless you are aged 18 and over\n"
source_yaml_url: https://artifacts.apis.io/compareasiagroup/eligibility/compareasiagroup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Compareasiagroup's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Comparison
- Asia
- Fintech
---
