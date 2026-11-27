---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content
    text: use it to create or distribute unlawful content
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mockko
provenance_date: '2026-11-10'
provider_name: Mockko
provider_slug: mockko
slug: mockko-eligibility
source_date: '2026-11-10'
source_filename: mockko-eligibility.yml
source_heading: Eligibility
source_page: https://mockko.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mockko\naid: mockko\nurl: https://mockko.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful content\n  text: use it to create or distribute unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create an account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mockko/eligibility/mockko-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Mockko's own page on 2026-11-10.
synthetic: false
tags:
- Dashboards
- Mockup
- Power BI
- Tableau
- Design
---
