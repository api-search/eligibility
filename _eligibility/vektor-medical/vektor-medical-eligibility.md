---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is offered and available to users who are older than 16 years of age and reside in the United States.
  entity_types:
  - text: By using the Website, you represent and warrant that you are at least 16 years of age, reside in the United States, and have the legal capacity to enter into a binding agreement with the Company.
    type: individual
  minimum_age:
    text: The Website is offered and available to users who are older than 16 years of age and reside in the United States.
    value: '16'
  restricted_uses:
  - summary: No commercial use
    text: You must not access or use for any commercial purposes any part of the Website or materials available through the Website.
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
name: Vektor Medical
provenance_date: '2026-11-10'
provider_name: Vektor Medical
provider_slug: vektor-medical
slug: vektor-medical-eligibility
source_date: '2026-11-10'
source_filename: vektor-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.vektormedical.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vektor Medical\naid: vektor-medical\nurl: https://www.vektormedical.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is offered and available to users who are older than 16 years of age and reside in the United\n    States.\nentity_types:\n- type: individual\n  text: By using the Website, you represent and warrant that you are at least 16 years of age, reside in the United\n    States, and have the legal capacity to enter into a binding agreement with the Company.\nrestricted_uses:\n- summary: No commercial use\n  text: You must not access or\
  \ use for any commercial purposes any part of the Website or materials available through\n    the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Website is offered and available to users who are older than 16 years of age and reside in the United\n    States.\n"
source_yaml_url: https://artifacts.apis.io/vektor-medical/eligibility/vektor-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vektor Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Cardiology
- Electrophysiology
- Artificial Intelligence
- Software as a Medical Device
- Diagnostics
---
