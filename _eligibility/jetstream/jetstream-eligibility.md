---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended solely for individuals who are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: The Site is intended solely for individuals who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Malicious, illegal or fraudulent use
    text: Use the Site in any manner that is malicious, deceptive, illegal, or fraudulent
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
name: Jetstream
provenance_date: '2026-11-09'
provider_name: Jetstream
provider_slug: jetstream
slug: jetstream-eligibility
source_date: '2026-11-09'
source_filename: jetstream-eligibility.yml
source_heading: Eligibility
source_page: https://jetstream.security/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jetstream\naid: jetstream\nurl: https://jetstream.security/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended solely for individuals who are eighteen (18) years of age or older.\nrestricted_uses:\n- summary: Malicious, illegal or fraudulent use\n  text: Use the Site in any manner that is malicious, deceptive, illegal, or fraudulent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended solely for individuals\
  \ who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/jetstream/eligibility/jetstream-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jetstream's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- AI Governance
- AI Security
- AI Agents
- Runtime Governance
- Compliance
- FinOps
---
