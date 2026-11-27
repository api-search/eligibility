---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Prices are per company, per app, and exclude sales tax where it applies.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information
    text: don't upload protected health information — the apps are not built for it and we do not sign business associate agreements.
  - summary: Not compliance or legal advice
    text: Artificl apps help you see what is expiring. They do not determine which documents you must keep, whether a certificate is adequate, or whether you are in compliance with any law, regulation or contract.
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
name: artificl-us
provenance_date: '2026-11-09'
provider_name: artificl-us
provider_slug: artificl-us
slug: artificl-us-eligibility
source_date: '2026-11-09'
source_filename: artificl-us-eligibility.yml
source_heading: Eligibility
source_page: https://artificl.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: artificl-us\naid: artificl-us\nurl: https://artificl.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Prices are per company, per app, and exclude sales tax where it applies.\nrestricted_uses:\n- summary: No protected health information\n  text: don't upload protected health information — the apps are not built for it and we do not sign business associate\n    agreements.\n- summary: Not compliance or legal advice\n  text: Artificl apps help you see what is expiring. They do not determine which documents you must keep, whether\n\
  \    a certificate is adequate, or whether you are in compliance with any law, regulation or contract.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/artificl-us/eligibility/artificl-us-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from artificl-us's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Artificial Intelligence
- Document Tracking
- Small Business
---
