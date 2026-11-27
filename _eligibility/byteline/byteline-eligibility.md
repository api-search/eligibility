---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Website and Products are intended solely for Users who are at least (18) years of age.
    type: individual
  minimum_age:
    text: Our Website and Products are intended solely for Users who are at least (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Unsolicited advertising and spam
    text: Contains any unsolicited or unauthorized advertising, solicitations, promotional materials, junk mail, spam, chain letters, pyramid schemes, or any other form of solicitation
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Byteline, Inc has sole right and discretion to decide whether to accept a Member and may reject a Member's registration with or without explanation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Byteline
provenance_date: '2026-11-09'
provider_name: Byteline
provider_slug: byteline
slug: byteline-eligibility
source_date: '2026-11-09'
source_filename: byteline-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.byteline.io/terms_conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Byteline\naid: byteline\nurl: https://cdn.byteline.io/terms_conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Website and Products are intended solely for Users who are at least (18) years of age.\nrestricted_uses:\n- summary: Unsolicited advertising and spam\n  text: Contains any unsolicited or unauthorized advertising, solicitations, promotional materials, junk mail, spam,\n    chain letters, pyramid schemes, or any other form of solicitation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: Byteline, Inc has sole right and discretion to decide whether to accept a Member and may reject a Member's\n    registration with or without explanation.\nminimum_age:\n  value: '18'\n  text: Our Website and Products are intended solely for Users who are at least (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/byteline/eligibility/byteline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Byteline's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Sync
- Automation
- Integration
- Software-as-a-Service
---
