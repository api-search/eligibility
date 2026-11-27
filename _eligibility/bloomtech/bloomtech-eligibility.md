---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: represent that you are at least 18 years of age and capable of agreeing to the Terms, or if you are under 18, that your parent or guardian has provided consent for you to access and use the Services
    type: individual
  minimum_age:
    text: represent that you are at least 18 years of age and capable of agreeing to the Terms, or if you are under 18, that your parent or guardian has provided consent
    value: '18'
  restricted_uses:
  - summary: Access from jurisdictions where illegal
    text: access the Service from a jurisdiction where it is illegal or unauthorized.
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
name: BloomTech
provenance_date: '2026-11-09'
provider_name: BloomTech
provider_slug: bloomtech
slug: bloomtech-eligibility
source_date: '2026-11-09'
source_filename: bloomtech-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomtech.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BloomTech\naid: bloomtech\nurl: https://www.bloomtech.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: represent that you are at least 18 years of age and capable of agreeing to the Terms, or if you are under\n    18, that your parent or guardian has provided consent for you to access and use the Services\nrestricted_uses:\n- summary: Access from jurisdictions where illegal\n  text: access the Service from a jurisdiction where it is illegal or unauthorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: represent that you are at least 18 years of age and capable of agreeing to the Terms, or if you are under\n    18, that your parent or guardian has provided consent\n"
source_yaml_url: https://artifacts.apis.io/bloomtech/eligibility/bloomtech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BloomTech's own page on 2026-11-09.
synthetic: false
tags:
- Coding Bootcamp
- Developer Training
- AI‑Integrated Learning
- Career Support
- Deferred Tuition
---
