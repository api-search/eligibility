---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Business Insider is not intended for children under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses of the Sites
    text: You may use the Sites only for lawful purposes and in accordance with these Terms of Service.
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
name: Business Insider
provenance_date: '2026-11-09'
provider_name: Business Insider
provider_slug: business-insider
slug: business-insider-eligibility
source_date: '2026-11-09'
source_filename: business-insider-eligibility.yml
source_heading: Eligibility
source_page: https://www.businessinsider.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Business Insider\naid: business-insider\nurl: https://www.businessinsider.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses of the Sites\n  text: You may use the Sites only for lawful purposes and in accordance with these Terms of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Business Insider is not intended for children under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/business-insider/eligibility/business-insider-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Business Insider's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- News
- Business
- Finance
- Technology
- Publishing
---
