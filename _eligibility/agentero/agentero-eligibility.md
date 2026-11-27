---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Insurance policyholders and consumers of insurance products and policies to manage insurance policies
    type: individual
  - text: solely for Your personal or business insurance purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Files limited to insurance policy documents
    text: You agree that any files uploaded to the Agentero Platform will be insurance policy documents. You will not upload any files that are not insurance policy documents.
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
name: Agentero
provenance_date: '2026-11-09'
provider_name: Agentero
provider_slug: agentero
slug: agentero-eligibility
source_date: '2026-11-09'
source_filename: agentero-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentero.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentero\naid: agentero\nurl: https://www.agentero.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Insurance policyholders and consumers of insurance products and policies to manage insurance policies\n- type: business\n  text: solely for Your personal or business insurance purposes\nrestricted_uses:\n- summary: Files limited to insurance policy documents\n  text: You agree that any files uploaded to the Agentero Platform will be insurance policy documents. You will\n    not upload any files that are not insurance\
  \ policy documents.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentero/eligibility/agentero-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Agentero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Insurance Agents
- Property and Casualty
- Agency Network
- Carrier Access
- Compliance
---
