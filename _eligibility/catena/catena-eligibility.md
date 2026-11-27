---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be a Sanctions Target or organized, resident, or located in a jurisdiction subject to comprehensive Sanctions. Catena may deny, condition, or restrict access to the Services in any jurisdiction at its discretion.
  entity_types:
  - text: The Services are offered to businesses and to individuals acting for business or commercial purposes.
    type: business
  - text: If you are a natural person, you must be at least eighteen (18) years old, have the legal capacity to form a binding contract, and access and use the Services solely for business or commercial purposes.
    type: individual
  minimum_age:
    text: If you are a natural person, you must be at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Personal, family or household use
    text: You represent and warrant that you are accessing and using the Services solely for business or commercial purposes and not for personal, family, or household purposes.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Catena may require you to complete identity verification, “know your customer” or “know your business,” beneficial ownership, and other onboarding and compliance procedures as a condition of access, and may condition, suspend, or terminate access based on the results.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Catena
provenance_date: '2026-11-09'
provider_name: Catena
provider_slug: catena
slug: catena-eligibility
source_date: '2026-11-09'
source_filename: catena-eligibility.yml
source_heading: Eligibility
source_page: https://catena.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Catena\naid: catena\nurl: https://catena.com/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be a Sanctions Target or organized, resident, or located in a jurisdiction subject to comprehensive\n    Sanctions. Catena may deny, condition, or restrict access to the Services in any jurisdiction at its discretion.\nentity_types:\n- type: business\n  text: The Services are offered to businesses and to individuals acting for business or commercial purposes.\n- type: individual\n  text: If you are a natural person, you must be at least eighteen (18) years old, have\
  \ the legal capacity to form\n    a binding contract, and access and use the Services solely for business or commercial purposes.\nrestricted_uses:\n- summary: Personal, family or household use\n  text: You represent and warrant that you are accessing and using the Services solely for business or commercial\n    purposes and not for personal, family, or household purposes.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Catena may require you to complete identity verification, “know your customer” or “know your business,”\n    beneficial ownership, and other onboarding and compliance procedures as a condition of access, and may condition,\n    suspend, or terminate access based on the results.\nminimum_age:\n  value: '18'\n  text: If you are a natural person, you must be at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/catena/eligibility/catena-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Catena's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Agentic Finance
- AI Agents
- Payments
- Stablecoins
- Governance
- Fintech
---
