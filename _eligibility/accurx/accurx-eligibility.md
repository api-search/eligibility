---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: knowingly access, store, distribute or transmit any Viruses or any material during the course of their use of the Platform that contains profanities or expletives, is unlawful, harmful, abusive, infringing, offensive, discriminatory, or which facilitates illegal activity
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Accurx may accept, propose amends to, or reject an Order Form in its absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accurx
provenance_date: '2026-11-09'
provider_name: Accurx
provider_slug: accurx
slug: accurx-eligibility
source_date: '2026-11-09'
source_filename: accurx-eligibility.yml
source_heading: Eligibility
source_page: https://www.accurx.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accurx\naid: accurx\nurl: https://www.accurx.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: knowingly access, store, distribute or transmit any Viruses or any material during the course of their use\n    of the Platform that contains profanities or expletives, is unlawful, harmful, abusive, infringing, offensive,\n    discriminatory, or which facilitates illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text:\
  \ Accurx may accept, propose amends to, or reject an Order Form in its absolute discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accurx/eligibility/accurx-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Accurx's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United Kingdom
- Clinical Communication
- NHS
- National Health System
- Interoperability
- FHIR
- HL7
- Primary Care
- Clinical AI
- Patient Engagement
- Telehealth
---
