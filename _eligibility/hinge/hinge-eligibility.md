---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: You are an individual (i.e., not any body corporate, partnership or other business entity) at least 18 years old
    type: individual
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No harmful, illegal or nefarious use
    text: Use our Services for any harmful, illegal, or nefarious purpose
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: Hinge does not conduct criminal background or identity verification checks on its users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hinge
provenance_date: '2026-11-09'
provider_name: Hinge
provider_slug: hinge
slug: hinge-eligibility
source_date: '2026-11-09'
source_filename: hinge-eligibility.yml
source_heading: Eligibility
source_page: https://hinge.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hinge\naid: hinge\nurl: https://hinge.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: You are an individual (i.e., not any body corporate, partnership or other business entity) at least 18 years\n    old\nrestricted_uses:\n- summary: No harmful, illegal or nefarious use\n  text: Use our Services for any harmful, illegal, or nefarious purpose\n\
  verification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: Hinge does not conduct criminal background or identity verification checks on its users.\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/hinge/eligibility/hinge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hinge's own page on 2026-11-09.
synthetic: false
tags:
- Dating
- Relationships
- Consumer App
- Mobile
- Match Group
- Social
---
