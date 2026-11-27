---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged thirteen (13) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your own personal and non-commercial use
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
name: Raven
provenance_date: '2026-11-10'
provider_name: Raven
provider_slug: raven
slug: raven-eligibility
source_date: '2026-11-10'
source_filename: raven-eligibility.yml
source_heading: Eligibility
source_page: https://raven.io/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raven\naid: raven\nurl: https://raven.io/terms-of-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for your own personal and non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/raven/eligibility/raven-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Raven's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Application Security
- Runtime Security
- Cybersecurity
- Cloud Security
- Kubernetes
- Vulnerability Management
---
