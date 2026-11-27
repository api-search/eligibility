---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are of legal age to form a binding contract, or, if you are a minor, you have your parent's permission to use the HeavyConnect Service
    type: individual
  - text: If you accept or agree to these Terms of Service on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms of Service
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract, or, if you are a minor, you have your parent's permission to use the HeavyConnect Service
    value: legal age to form a binding contract
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
name: HeavyConnect
provenance_date: '2026-11-09'
provider_name: HeavyConnect
provider_slug: heavyconnect
slug: heavyconnect-eligibility
source_date: '2026-11-09'
source_filename: heavyconnect-eligibility.yml
source_heading: Eligibility
source_page: https://www.heavyconnect.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HeavyConnect\naid: heavyconnect\nurl: https://www.heavyconnect.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract, or, if you are a minor, you have your parent's permission\n    to use the HeavyConnect Service\n- type: business\n  text: If you accept or agree to these Terms of Service on behalf of a company or other legal entity, you represent\n    and warrant that you have the authority to bind that company or other legal entity to these Terms of Service\nrestricted_uses: []\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: you are of legal age to form a binding contract, or, if you are a minor, you have your parent's permission\n    to use the HeavyConnect Service\n"
source_yaml_url: https://artifacts.apis.io/heavyconnect/eligibility/heavyconnect-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from HeavyConnect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Food Safety
- Compliance
- Traceability
- Workforce Management
- Quality Assurance
- AgTech
---
