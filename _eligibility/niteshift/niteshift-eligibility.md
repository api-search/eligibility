---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for business use by users and companies located in the United States.
  entity_types:
  - text: The Service is intended for business use by users and companies located in the United States.
    type: business
  minimum_age:
    text: you are at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Sensitive regulated data
    text: you will not submit protected health information, payment card information, or other regulated sensitive data to the Service
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
name: Niteshift
provenance_date: '2026-11-10'
provider_name: Niteshift
provider_slug: niteshift
slug: niteshift-eligibility
source_date: '2026-11-10'
source_filename: niteshift-eligibility.yml
source_heading: Eligibility
source_page: https://niteshift.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Niteshift\naid: niteshift\nurl: https://niteshift.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for business use by users and companies located in the United States.\nentity_types:\n- type: business\n  text: The Service is intended for business use by users and companies located in the United States.\nrestricted_uses:\n- summary: Sensitive regulated data\n  text: you will not submit protected health information, payment card information, or other regulated sensitive\n    data to the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/niteshift/eligibility/niteshift-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Niteshift's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Coding Agents
- AI Agents
- Developer Tools
- Cloud Development Environments
- DevOps
- Automation
---
