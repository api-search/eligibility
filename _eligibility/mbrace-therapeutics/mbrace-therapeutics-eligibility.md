---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is intended to be available to users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: This Website is intended to be available to users who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: No medical advice; informational only
    text: The Website does not, and is not intended to, provide any medical advice.
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
name: MBrace Therapeutics
provenance_date: '2026-11-10'
provider_name: MBrace Therapeutics
provider_slug: mbrace-therapeutics
slug: mbrace-therapeutics-eligibility
source_date: '2026-11-10'
source_filename: mbrace-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://mbracetrx.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MBrace Therapeutics\naid: mbrace-therapeutics\nurl: https://mbracetrx.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is intended to be available to users who are 13 years of age or older.\nrestricted_uses:\n- summary: No medical advice; informational only\n  text: The Website does not, and is not intended to, provide any medical advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is intended to be available to users\
  \ who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/mbrace-therapeutics/eligibility/mbrace-therapeutics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from MBrace Therapeutics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Oncology
- Antibody-Drug Conjugates
- Drug Discovery
- Clinical Trials
- Life Sciences
- Precision Medicine
- content-api
---
