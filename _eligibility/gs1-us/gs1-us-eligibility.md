---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Commercial or political use
    text: use the Sites for any political or commercial purpose
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
name: GS1 US
provenance_date: '2026-11-09'
provider_name: GS1 US
provider_slug: gs1-us
slug: gs1-us-eligibility
source_date: '2026-11-09'
source_filename: gs1-us-eligibility.yml
source_heading: Eligibility
source_page: https://www.gs1us.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GS1 US\naid: gs1-us\nurl: https://www.gs1us.org/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial or political use\n  text: use the Sites for any political or commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/gs1-us/eligibility/gs1-us-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from GS1 US's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Standards
- Barcodes
- Supply Chain
- Data
---
