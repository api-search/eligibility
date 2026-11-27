---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, you must be at least 18 years of age and located within the United States to use our Services.
  entity_types:
  - text: you must be at least 18 years of age and located within the United States to use our Services.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age and located within the United States to use our Services.
    value: '18'
  restricted_uses:
  - summary: Personal use only; no resale
    text: Products and services purchased through the website are for personal, non-commercial use only.
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
name: Everly Health
provenance_date: '2026-11-09'
provider_name: Everly Health
provider_slug: everly-health
slug: everly-health-eligibility
source_date: '2026-11-09'
source_filename: everly-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.everlywell.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everly Health\naid: everly-health\nurl: https://www.everlywell.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, you must be at least 18 years of age and located within the United States to\n    use our Services.\nentity_types:\n- type: individual\n  text: you must be at least 18 years of age and located within the United States to use our Services.\nrestricted_uses:\n- summary: Personal use only; no resale\n  text: Products and services purchased through the website are for personal, non-commercial use only.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age and located within the United States to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/everly-health/eligibility/everly-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Everly Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Diagnostics
- Lab Testing
- Telehealth
- Consumer Health
- Identity
---
