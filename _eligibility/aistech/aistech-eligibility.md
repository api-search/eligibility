---
claim_count: 1
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
  - summary: Fraudulent or misleading purposes
    text: Using the website for fraudulent or misleading purposes
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
name: Aistech
provenance_date: '2026-11-09'
provider_name: Aistech
provider_slug: aistech
slug: aistech-eligibility
source_date: '2026-11-09'
source_filename: aistech-eligibility.yml
source_heading: Eligibility
source_page: https://aistechspace.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aistech\naid: aistech\nurl: https://aistechspace.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or misleading purposes\n  text: Using the website for fraudulent or misleading purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aistech/eligibility/aistech-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aistech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Space
- Satellite
- Thermal Imagery
- Geospatial Intelligence
---
