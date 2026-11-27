---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: this site is intended for general audiences 18 years of age and older. Access by anyone younger is not authorized.
    type: individual
  minimum_age:
    text: this site is intended for general audiences 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: You agree that in no event shall your use or access to the Website be for commercial purposes.
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
name: Medix Infusion
provenance_date: '2026-11-10'
provider_name: Medix Infusion
provider_slug: medix-infusion
slug: medix-infusion-eligibility
source_date: '2026-11-10'
source_filename: medix-infusion-eligibility.yml
source_heading: Eligibility
source_page: https://medixinfusion.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medix Infusion\naid: medix-infusion\nurl: https://medixinfusion.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: this site is intended for general audiences 18 years of age and older. Access by anyone younger is not authorized.\nrestricted_uses:\n- summary: Commercial purposes\n  text: You agree that in no event shall your use or access to the Website be for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: this site is intended\
  \ for general audiences 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/medix-infusion/eligibility/medix-infusion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Medix Infusion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Infusion Therapy
- Specialty Pharmacy
- Home Care
- Ambulatory Care
- Patient Care
- Texas
---
