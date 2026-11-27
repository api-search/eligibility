---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: the Service and Software are not for use by children (persons under the age of 18).
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You will only use the Service or Software for lawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You will provide us with whatever proof of identity we may reasonably request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Naborforce
provenance_date: '2026-11-10'
provider_name: Naborforce
provider_slug: naborforce
slug: naborforce-eligibility
source_date: '2026-11-10'
source_filename: naborforce-eligibility.yml
source_heading: Eligibility
source_page: https://naborforce.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Naborforce\naid: naborforce\nurl: https://naborforce.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You will only use the Service or Software for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You will provide us with whatever proof of identity we may reasonably request.\nminimum_age:\n  value: '18'\n  text: the Service and Software are not for use by children (persons under the age of 18).\n"
source_yaml_url: https://artifacts.apis.io/naborforce/eligibility/naborforce-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Naborforce's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Care
- Aging
- Senior Care
- Caregiving
- On-Demand Services
- Health
- Marketplace
---
