---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services
    type: individual
  - text: if you are an entity, organization or company, the individual accepting these Terms has the authority to bind such an entity, organization or company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services
    value: '18'
  restricted_uses:
  - summary: Export/sanctions restrictions
    text: You represent, warrant and covenant that you are not (i) located in or a resident of any country that is the subject of comprehensive U.S. sanctions
  - summary: Watts personal use only
    text: Watts may be used for personal use only; any commercial or business use is prohibited.
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
name: Ohmconnect
provenance_date: '2026-11-10'
provider_name: Ohmconnect
provider_slug: ohmconnect
slug: ohmconnect-eligibility
source_date: '2026-11-10'
source_filename: ohmconnect-eligibility.yml
source_heading: Eligibility
source_page: https://www.ohmconnect.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ohmconnect\naid: ohmconnect\nurl: https://www.ohmconnect.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services\n- type: business\n  text: if you are an entity, organization or company, the individual accepting these Terms has the authority to\n    bind such an entity, organization or company to these Terms.\nrestricted_uses:\n- summary: Export/sanctions restrictions\n  text: You represent, warrant and covenant that you are not (i) located in or\
  \ a resident of any country that is\n    the subject of comprehensive U.S. sanctions\n- summary: Watts personal use only\n  text: Watts may be used for personal use only; any commercial or business use is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services\n"
source_yaml_url: https://artifacts.apis.io/ohmconnect/eligibility/ohmconnect-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ohmconnect's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Demand Response
- Virtual Power Plant
- Utilities
- Smart Home
- Sustainability
- Electricity
---
