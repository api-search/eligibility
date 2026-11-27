---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: This site is intended for visitors from Canada only, who have reached the age of majority in their jurisdiction of residence.
  minimum_age:
    text: This site is intended for visitors from Canada only, who have reached the age of majority in their jurisdiction of residence.
    value: age of majority
  restricted_uses:
  - summary: No violating laws
    text: You agree that your use of the site shall not violate any applicable local, national, provincial/territorial, or international law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All purchases are subject to verification by Sonnet at any time and for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sonnet Insurance
provenance_date: '2026-11-10'
provider_name: Sonnet Insurance
provider_slug: sonnet-insurance
slug: sonnet-insurance-eligibility
source_date: '2026-11-10'
source_filename: sonnet-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.sonnet.ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sonnet Insurance\naid: sonnet-insurance\nurl: https://www.sonnet.ca/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: This site is intended for visitors from Canada only, who have reached the age of majority in their jurisdiction\n    of residence.\nentity_types: []\nrestricted_uses:\n- summary: No violating laws\n  text: You agree that your use of the site shall not violate any applicable local, national, provincial/territorial,\n    or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All purchases are subject to verification\
  \ by Sonnet at any time and for any reason.\nminimum_age:\n  value: age of majority\n  text: This site is intended for visitors from Canada only, who have reached the age of majority in their jurisdiction\n    of residence.\n"
source_yaml_url: https://artifacts.apis.io/sonnet-insurance/eligibility/sonnet-insurance-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sonnet Insurance's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Auto Insurance
- Home Insurance
- Insurtech
- Direct to Consumer
- Underwriting
- Claims
---
