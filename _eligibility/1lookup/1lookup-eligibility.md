---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 21 says you represent you are not located in a country or region subject to comprehensive U.S. sanctions; no specific countries are named.
  entity_types:
  - text: The Service is intended for business use. It is not offered for personal, family, or household purposes.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into a contract.
    value: '18'
  restricted_uses:
  - summary: No sensitive data submission
    text: You must not submit to the Service any government-issued identification numbers, payment card or financial account numbers, health or medical information, biometric or genetic data, precise geolocation
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
name: 1Lookup
provenance_date: '2026-11-09'
provider_name: 1Lookup
provider_slug: 1lookup
slug: 1lookup-eligibility
source_date: '2026-11-09'
source_filename: 1lookup-eligibility.yml
source_heading: Eligibility
source_page: https://www.1lookup.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1Lookup\naid: 1lookup\nurl: https://www.1lookup.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Section 21 says you represent you are not located in a country or region subject to comprehensive U.S. sanctions;\n    no specific countries are named.\nentity_types:\n- type: business\n  text: The Service is intended for business use. It is not offered for personal, family, or household purposes.\nrestricted_uses:\n- summary: No sensitive data submission\n  text: You must not submit to the Service any government-issued identification numbers, payment card or financial\n    account\
  \ numbers, health or medical information, biometric or genetic data, precise geolocation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into a contract.\n"
source_yaml_url: https://artifacts.apis.io/1lookup/eligibility/1lookup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 1Lookup's own page on 2026-11-09.
synthetic: false
tags:
- Phone Validation
- Email Verification
- IP Intelligence
- Fraud and Risk
- Data Enrichment
- B2B contact & company data
- SEO / web analytics
- Audio Transcription
- MCP / agent-native
- REST API
---
