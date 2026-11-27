---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a natural person who actually uses the brokered carriage services
    type: individual
  - text: a service for legal persons that buy carriage services for their own needs or as a broker.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Children travelling without adult or consent
    text: The BROKER does not conduct the brokerage of the carriage of GROUPS OF CHILDREN or of individual persons less than fifteen (15) years old without an accompanying adult or a written consent of the legal guardian
  - summary: Animals
    text: nor the brokerage of the carriage of animals without a preliminary written approval of the BROKER
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
name: GoOpti
provenance_date: '2026-11-09'
provider_name: GoOpti
provider_slug: goopti
slug: goopti-eligibility
source_date: '2026-11-09'
source_filename: goopti-eligibility.yml
source_heading: Eligibility
source_page: https://www.goopti.com/en/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoOpti\naid: goopti\nurl: https://www.goopti.com/en/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a natural person who actually uses the brokered carriage services\n- type: business\n  text: a service for legal persons that buy carriage services for their own needs or as a broker.\nrestricted_uses:\n- summary: Children travelling without adult or consent\n  text: The BROKER does not conduct the brokerage of the carriage of GROUPS OF CHILDREN or of individual persons\n    less than fifteen\
  \ (15) years old without an accompanying adult or a written consent of the legal guardian\n- summary: Animals\n  text: nor the brokerage of the carriage of animals without a preliminary written approval of the BROKER\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goopti/eligibility/goopti-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from GoOpti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Travel
- Mobility
- Airport Transfers
- Ride Booking
- Marketplace
---
