---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your own personal, noncommercial use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use of website
    text: Sell, resell or commercially use our Website;
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
name: Harmonycares
provenance_date: '2026-11-09'
provider_name: Harmonycares
provider_slug: harmonycares
slug: harmonycares-eligibility
source_date: '2026-11-09'
source_filename: harmonycares-eligibility.yml
source_heading: Eligibility
source_page: https://harmonycares.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harmonycares\naid: harmonycares\nurl: https://harmonycares.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your own personal, noncommercial use\nrestricted_uses:\n- summary: No commercial use of website\n  text: Sell, resell or commercially use our Website;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/harmonycares/eligibility/harmonycares-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Harmonycares's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Primary Care
- Value-Based Care
- Medicare
- Palliative Care
- Telehealth
---
