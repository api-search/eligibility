---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not all features, content, products and services may be available to all persons or geographic locations
  minimum_age:
    text: You must be at least 18 years old to use the Service
    value: '18'
  restricted_uses:
  - summary: Commercial or business use
    text: Access or use the Service for any commercial or business purpose
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
name: Carbon
provenance_date: '2026-11-09'
provider_name: Carbon
provider_slug: carbon
slug: carbon-eligibility
source_date: '2026-11-09'
source_filename: carbon-eligibility.yml
source_heading: Eligibility
source_page: https://www.carbon3d.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carbon\naid: carbon\nurl: https://www.carbon3d.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not all features, content, products and services may be available to all persons or geographic locations\nentity_types: []\nrestricted_uses:\n- summary: Commercial or business use\n  text: Access or use the Service for any commercial or business purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/carbon/eligibility/carbon-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Carbon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Frontier Tech
- 3D Printing
- Digital Manufacturing
- Hardware
- Materials Science
---
