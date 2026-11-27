---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Serving Southern California
  entity_types:
  - text: We connect restaurant operators with vetted, pre-screened service providers for on-demand repairs and scheduled maintenance services.
    type: business
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: you will not use the Site for any unlawful purpose
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
name: Boh
provenance_date: '2026-11-09'
provider_name: Boh
provider_slug: boh
slug: boh-eligibility
source_date: '2026-11-09'
source_filename: boh-eligibility.yml
source_heading: Eligibility
source_page: https://boh.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boh\naid: boh\nurl: https://boh.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Serving Southern California\nentity_types:\n- type: business\n  text: We connect restaurant operators with vetted, pre-screened service providers for on-demand repairs and scheduled\n    maintenance services.\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: you will not use the Site for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/boh/eligibility/boh-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Boh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Restaurant
- Maintenance
- Compliance
- Repair
---
