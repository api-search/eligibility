---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis without professional guidance
    text: This device should not be used to diagnose, treat, or prevent any medical conditions without the guidance of a qualified healthcare professional.
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
name: Medivis
provenance_date: '2026-11-10'
provider_name: Medivis
provider_slug: medivis
slug: medivis-eligibility
source_date: '2026-11-10'
source_filename: medivis-eligibility.yml
source_heading: Eligibility
source_page: https://www.medivis.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medivis\naid: medivis\nurl: https://www.medivis.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service\nrestricted_uses:\n- summary: Not for diagnosis without professional guidance\n  text: This device should not be used to diagnose, treat, or prevent any medical conditions without the guidance\n    of a qualified healthcare professional.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/medivis/eligibility/medivis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Medivis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hardware
- Healthcare
- Augmented Reality
- Surgical Navigation
- Medical Imaging
- Medical Education
- Health Tech
---
