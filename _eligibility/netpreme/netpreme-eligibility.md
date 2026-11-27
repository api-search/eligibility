---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Sites are not intended for use by children under age 18 (or the age of majority in your jurisdiction if it is greater than age 18).
    type: individual
  - text: If you are an individual accessing or using the Sites on behalf of, or for the benefit of any business entity or other entity with which you are associated (an “Organization”), then you are agreeing to these Terms on behalf of yourself and such Organization
    type: business
  minimum_age:
    text: By using the Sites, you represent and warrant that you are at least 18 years of age (or the age of majority in your jurisdiction).
    value: '18'
  restricted_uses:
  - summary: Competitors and benchmarking
    text: If you are a competitor, or for purposes of monitoring the Sites’ availability, performance or functionality, or for any other benchmarking or competitive purposes.
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
name: Netpreme
provenance_date: '2026-11-10'
provider_name: Netpreme
provider_slug: netpreme
slug: netpreme-eligibility
source_date: '2026-11-10'
source_filename: netpreme-eligibility.yml
source_heading: Eligibility
source_page: https://netpreme.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Netpreme\naid: netpreme\nurl: https://netpreme.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Sites are not intended for use by children under age 18 (or the age of majority in your jurisdiction\n    if it is greater than age 18).\n- type: business\n  text: If you are an individual accessing or using the Sites on behalf of, or for the benefit of any business entity\n    or other entity with which you are associated (an “Organization”), then you are agreeing to these Terms on behalf\n    of yourself and such Organization\n\
  restricted_uses:\n- summary: Competitors and benchmarking\n  text: If you are a competitor, or for purposes of monitoring the Sites’ availability, performance or functionality,\n    or for any other benchmarking or competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Sites, you represent and warrant that you are at least 18 years of age (or the age of majority\n    in your jurisdiction).\n"
source_yaml_url: https://artifacts.apis.io/netpreme/eligibility/netpreme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Netpreme's own page on 2026-11-10.
synthetic: false
tags:
- Memory Systems
- AI Compute
- MPU
- Inference Hardware
- GPU Memory
- Silicon
---
