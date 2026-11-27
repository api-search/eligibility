---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We operate our website from the United States and it is intended for US residents.
  entity_types:
  - text: individuals 18 years of age and older for their own personal use
    type: individual
  minimum_age:
    text: individuals 18 years of age and older
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You may only use the Website for lawful purposes in accordance with these Terms.
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
name: Arcadian Infracom
provenance_date: '2026-11-09'
provider_name: Arcadian Infracom
provider_slug: arcadian-infracom
slug: arcadian-infracom-eligibility
source_date: '2026-11-09'
source_filename: arcadian-infracom-eligibility.yml
source_heading: Eligibility
source_page: https://arcadianinfra.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcadian Infracom\naid: arcadian-infracom\nurl: https://arcadianinfra.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We operate our website from the United States and it is intended for US residents.\nentity_types:\n- type: individual\n  text: individuals 18 years of age and older for their own personal use\nrestricted_uses:\n- summary: Lawful use only\n  text: You may only use the Website for lawful purposes in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: individuals 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/arcadian-infracom/eligibility/arcadian-infracom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arcadian Infracom's own page on 2026-11-09.
synthetic: false
tags:
- Infrastructure
- Fiber
- Broadband
- Rural Connectivity
- St. Louis
---
