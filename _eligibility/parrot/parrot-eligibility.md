---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not access or use the Service from within any Embargoed Countries (not named on page).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: You may not access any Services or Software if you are a direct competitor to Parrot
  - summary: HIPAA/PHI only with BAA
    text: without first informing Parrot in writing in accordance with this Agreement and then executing a business associate agreement with Parrot
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
name: Parrot
provenance_date: '2026-11-10'
provider_name: Parrot
provider_slug: parrot
slug: parrot-eligibility
source_date: '2026-11-10'
source_filename: parrot-eligibility.yml
source_heading: Eligibility
source_page: https://www.parrot.us/agreements/terms-and-conditions-01-15-2025
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parrot\naid: parrot\nurl: https://www.parrot.us/agreements/terms-and-conditions-01-15-2025\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not access or use the Service from within any Embargoed Countries (not named on page).\nentity_types: []\nrestricted_uses:\n- summary: Direct competitors barred\n  text: You may not access any Services or Software if you are a direct competitor to Parrot\n- summary: HIPAA/PHI only with BAA\n  text: without first informing Parrot in writing in accordance with this Agreement and then executing a business\n    associate agreement with\
  \ Parrot\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/parrot/eligibility/parrot-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Parrot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Legal Tech
- Court Reporting
- Deposition
- Transcription
- Insurance
- Medical Records
- Litigation
---
