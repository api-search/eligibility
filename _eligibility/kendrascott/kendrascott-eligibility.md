---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Club Kendra membership is only available to legal residents of the United States. International customers are not eligible for Club Kendra membership.
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: Consumer-only resale restriction
    text: Resale Products on www.kendrascott.com are intended for consumers only.
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
name: Kendra Scott
provenance_date: '2026-11-09'
provider_name: Kendra Scott
provider_slug: kendrascott
slug: kendrascott-eligibility
source_date: '2026-11-09'
source_filename: kendrascott-eligibility.yml
source_heading: Eligibility
source_page: https://www.kendrascott.com/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kendra Scott\naid: kendrascott\nurl: https://www.kendrascott.com/terms-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Club Kendra membership is only available to legal residents of the United States. International customers\n    are not eligible for Club Kendra membership.\nentity_types: []\nrestricted_uses:\n- summary: Consumer-only resale restriction\n  text: Resale Products on www.kendrascott.com are intended for consumers only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/kendrascott/eligibility/kendrascott-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kendra Scott's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Jewelry
- E-Commerce
- Consumer
- Accessories
---
