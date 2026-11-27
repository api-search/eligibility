---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged eighteen (18) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged eighteen (18) years or older.
    value: '18'
  restricted_uses:
  - summary: Malicious, illegal or fraudulent use
    text: use the Site in any manner that is otherwise malicious, illegal or fraudulent
  - summary: Impersonation
    text: impersonate another person or entity or use a deceptive identity to mislead others about who you are
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
name: Astelia
provenance_date: '2026-11-09'
provider_name: Astelia
provider_slug: astelia
slug: astelia-eligibility
source_date: '2026-11-09'
source_filename: astelia-eligibility.yml
source_heading: Eligibility
source_page: https://www.astelia.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astelia\naid: astelia\nurl: https://www.astelia.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\nrestricted_uses:\n- summary: Malicious, illegal or fraudulent use\n  text: use the Site in any manner that is otherwise malicious, illegal or fraudulent\n- summary: Impersonation\n  text: impersonate another person or entity or use a deceptive identity to mislead others about who you are\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/astelia/eligibility/astelia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Astelia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Vulnerability Management
- Exposure Management
- Attack Surface Management
- Cybersecurity
- Artificial Intelligence
- AI Agents
---
