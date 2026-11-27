---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company makes no representation that this Service or the Content is appropriate or available for use in other locations
  minimum_age:
    text: null
    value: null
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
name: Mimic
provenance_date: '2026-11-10'
provider_name: Mimic
provider_slug: mimic
slug: mimic-eligibility
source_date: '2026-11-10'
source_filename: mimic-eligibility.yml
source_heading: Eligibility
source_page: https://mimic.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mimic\naid: mimic\nurl: https://mimic.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company makes no representation that this Service or the Content is appropriate or available for use\n    in other locations\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mimic/eligibility/mimic-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Mimic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Cybersecurity
- Ransomware Defense
- Endpoint Security
- Threat Detection
- AI Security
- Software-as-a-Service
---
