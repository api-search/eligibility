---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Platform and accept these Terms.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Platform and accept these Terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful or disruptive use
    text: You agree to use the Platform only for lawful purposes and in accordance with these Terms.
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
name: CoverStack
provenance_date: '2026-11-09'
provider_name: CoverStack
provider_slug: coverstack
slug: coverstack-eligibility
source_date: '2026-11-09'
source_filename: coverstack-eligibility.yml
source_heading: Eligibility
source_page: https://coverstack.in/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoverStack\naid: coverstack\nurl: https://coverstack.in/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Platform and accept these Terms.\nrestricted_uses:\n- summary: Unlawful or disruptive use\n  text: You agree to use the Platform only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform\
  \ and accept these Terms.\n"
source_yaml_url: https://artifacts.apis.io/coverstack/eligibility/coverstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CoverStack's own page on 2026-11-09.
synthetic: false
tags:
- No-Code
- API Platform
- Data Integration
- Automation
- Software-as-a-Service
---
