---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The content on this website is intended solely for residents of the United States.
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
name: BioGaia
provenance_date: '2026-11-09'
provider_name: BioGaia
provider_slug: biogaia
slug: biogaia-eligibility
source_date: '2026-11-09'
source_filename: biogaia-eligibility.yml
source_heading: Eligibility
source_page: https://www.biogaia.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BioGaia\naid: biogaia\nurl: https://www.biogaia.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The content on this website is intended solely for residents of the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/biogaia/eligibility/biogaia-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from BioGaia's own page on 2026-11-09.
synthetic: false
tags:
- Probiotics
- Healthcare
- Sweden
- Gut Health
- Consumer Products
---
