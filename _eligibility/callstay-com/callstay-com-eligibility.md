---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 and able to enter into a binding contract.
    type: individual
  - text: If you book as a business, a travel arranger, an agency, or on behalf of clients, you may do so only with our written agreement
    type: business
  minimum_age:
    text: You are at least 18 and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Business bookings without agreement
    text: you may do so only with our written agreement
  - summary: Sanctions and export laws
    text: You will not use the service in breach of sanctions or export laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before we change, cancel or give details of a booking on a call, we check that we are speaking to the person who made it or to a guest on it
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Callstay
provenance_date: '2026-11-09'
provider_name: Callstay
provider_slug: callstay-com
slug: callstay-com-eligibility
source_date: '2026-11-09'
source_filename: callstay-com-eligibility.yml
source_heading: Eligibility
source_page: https://callstay.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Callstay\naid: callstay-com\nurl: https://callstay.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 and able to enter into a binding contract.\n- type: business\n  text: If you book as a business, a travel arranger, an agency, or on behalf of clients, you may do so only with\n    our written agreement\nrestricted_uses:\n- summary: Business bookings without agreement\n  text: you may do so only with our written agreement\n- summary: Sanctions and export laws\n  text: You will not use the service in breach\
  \ of sanctions or export laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before we change, cancel or give details of a booking on a call, we check that we are speaking to the person\n    who made it or to a guest on it\nminimum_age:\n  value: '18'\n  text: You are at least 18 and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/callstay-com/eligibility/callstay-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Callstay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Hotels
- Hotel Booking
- Accommodation
- Reservations
- MCP
- AI Agents
---
