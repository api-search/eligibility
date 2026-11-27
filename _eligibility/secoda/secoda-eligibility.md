---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual you are over eighteen years old
    type: individual
  - text: if you are opening an account on behalf of a company or other business you are authorised by that business to act on its behalf
    type: business
  minimum_age:
    text: if you are an individual you are over eighteen years old
    value: eighteen years old
  restricted_uses:
  - summary: Lawful use only
    text: You may only use Secoda for lawful purposes.
  - summary: No fraud or spam
    text: for the purposes of fraud, or to transmit unsolicited advertising or spam
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
name: Secoda
provenance_date: '2026-11-10'
provider_name: Secoda
provider_slug: secoda
slug: secoda-eligibility
source_date: '2026-11-10'
source_filename: secoda-eligibility.yml
source_heading: Eligibility
source_page: https://docs.secoda.co/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Secoda\naid: secoda\nurl: https://docs.secoda.co/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual you are over eighteen years old\n- type: business\n  text: if you are opening an account on behalf of a company or other business you are authorised by that business\n    to act on its behalf\nrestricted_uses:\n- summary: Lawful use only\n  text: You may only use Secoda for lawful purposes.\n- summary: No fraud or spam\n  text: for the purposes of fraud, or to transmit unsolicited advertising\
  \ or spam\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: eighteen years old\n  text: if you are an individual you are over eighteen years old\n"
source_yaml_url: https://artifacts.apis.io/secoda/eligibility/secoda-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Secoda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Data Catalog
- Data Governance
- Metadata
- Data Lineage
- Data Quality
- Data Discovery
- Observability
- AI Agents
---
