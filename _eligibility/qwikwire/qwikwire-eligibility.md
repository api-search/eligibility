---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least eighteen (18) years of age and possess the legal capacity to enter into these Terms
    type: individual
  - text: If you access or use the Platform on behalf of another individual or a legal entity, you further represent and warrant that you are duly authorized to act on behalf of such individual or entity
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age and possess the legal capacity to enter into these Terms
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: the Payer shall use the Platform only for lawful purposes and in accordance with these Terms and all applicable laws, rules, and regulations
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
name: Qwikwire
provenance_date: '2026-11-10'
provider_name: Qwikwire
provider_slug: qwikwire
slug: qwikwire-eligibility
source_date: '2026-11-10'
source_filename: qwikwire-eligibility.yml
source_heading: Eligibility
source_page: https://aqwire.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qwikwire\naid: qwikwire\nurl: https://aqwire.co/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age and possess the legal capacity to enter into these Terms\n- type: business\n  text: If you access or use the Platform on behalf of another individual or a legal entity, you further represent\n    and warrant that you are duly authorized to act on behalf of such individual or entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: the Payer shall use the Platform only\
  \ for lawful purposes and in accordance with these Terms and all applicable\n    laws, rules, and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age and possess the legal capacity to enter into these Terms\n"
source_yaml_url: https://artifacts.apis.io/qwikwire/eligibility/qwikwire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Qwikwire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Real Estate
- Fintech
- Philippines
- Multi-Currency
- Remittances
---
