---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this website you confirm that you are at least 16 years old , have the legal capacity to enter a binding agreement
    type: individual
  minimum_age:
    text: you are at least 16 years old
    value: '16'
  restricted_uses:
  - summary: Prohibited uses
    text: generate or facilitate spam; create malicious, deceptive, or illegal content; harass or abuse others
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
name: AETumi
provenance_date: '2026-11-09'
provider_name: AETumi
provider_slug: aetumi-app
slug: aetumi-app-eligibility
source_date: '2026-11-09'
source_filename: aetumi-app-eligibility.yml
source_heading: Eligibility
source_page: https://aetumi.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AETumi\naid: aetumi-app\nurl: https://aetumi.app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this website you confirm that you are at least 16 years old , have the legal capacity to enter\n    a binding agreement\nrestricted_uses:\n- summary: Prohibited uses\n  text: generate or facilitate spam; create malicious, deceptive, or illegal content; harass or abuse others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/aetumi-app/eligibility/aetumi-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AETumi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- 3DWeb
- Design Tools
- Software-as-a-Service
---
