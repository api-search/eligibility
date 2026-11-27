---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the right to bind such organization to this Agreement
    type: business
  minimum_age:
    text: you hereby represent that you are of legal age
    value: legal age
  restricted_uses:
  - summary: Personal non-commercial use only
    text: you are permitted to use the Service solely for your own personal, non-commercial use.
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
name: Workgrounds
provenance_date: '2026-11-10'
provider_name: Workgrounds
provider_slug: workgrounds
slug: workgrounds-eligibility
source_date: '2026-11-10'
source_filename: workgrounds-eligibility.yml
source_heading: Eligibility
source_page: https://workgrounds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workgrounds\naid: workgrounds\nurl: https://workgrounds.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the right to bind\n    such organization to this Agreement\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: you are permitted to use the Service solely for your own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text:\
  \ you hereby represent that you are of legal age\n"
source_yaml_url: https://artifacts.apis.io/workgrounds/eligibility/workgrounds-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Workgrounds's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Travel
- Hotels
- Automation
- Corporate
---
