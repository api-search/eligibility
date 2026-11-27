---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Unlawful purposes
    text: Use the Service for any unlawful purpose or in violation of any applicable law
  - summary: Impersonation
    text: Impersonate another person or entity
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
name: CiteMe
provenance_date: '2026-11-09'
provider_name: CiteMe
provider_slug: citeme-app
slug: citeme-app-eligibility
source_date: '2026-11-09'
source_filename: citeme-app-eligibility.yml
source_heading: Eligibility
source_page: https://citeme.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CiteMe\naid: citeme-app\nurl: https://citeme.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: Use the Service for any unlawful purpose or in violation of any applicable law\n- summary: Impersonation\n  text: Impersonate another person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/citeme-app/eligibility/citeme-app-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CiteMe's own page on 2026-11-09.
synthetic: false
tags:
- Citations
- Academic
- Tool
- Free
- Web App
---
