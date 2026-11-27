---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or inappropriate use
    text: Use the Website in any unlawful or inappropriate manner, as determined by 2U in their sole discretion
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
name: 2U
provenance_date: '2026-11-09'
provider_name: 2U
provider_slug: 2u
slug: 2u-eligibility
source_date: '2026-11-09'
source_filename: 2u-eligibility.yml
source_heading: Eligibility
source_page: https://2u.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 2U\naid: 2u\nurl: https://2u.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or inappropriate use\n  text: Use the Website in any unlawful or inappropriate manner, as determined by 2U in their sole discretion\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/2u/eligibility/2u-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from 2U's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- E-Learning
- Universities
- EDX
---
