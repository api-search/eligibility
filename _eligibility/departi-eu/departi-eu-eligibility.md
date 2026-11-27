---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to create an account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: Unlawful, abusive or false-data uses
    text: Submit false or misleading information to the compliance tracker
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
name: Departi
provenance_date: '2026-11-09'
provider_name: Departi
provider_slug: departi-eu
slug: departi-eu-eligibility
source_date: '2026-11-09'
source_filename: departi-eu-eligibility.yml
source_heading: Eligibility
source_page: https://departi.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Departi\naid: departi-eu\nurl: https://departi.eu/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to create an account.\nrestricted_uses:\n- summary: Unlawful, abusive or false-data uses\n  text: Submit false or misleading information to the compliance tracker\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/departi-eu/eligibility/departi-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Departi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Digital Nomads
- Accommodation
- Visa
- MCP
- AI Concierge
- Europe
---
