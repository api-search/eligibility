---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not represent or warrant that MyAccessHope is appropriate for use in any particular jurisdiction.
  entity_types:
  - text: AccessHope makes MyAccessHope and its features, tools and services available to the general public
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for medical diagnosis or treatment
    text: NOTHING IN MyAccessHope, WHETHER POSTED BY ACCESSHOPE OR OTHERWISE, IS INTENDED TO BE USED BY YOU OR ANY OTHER PERSON FOR MEDICAL DIAGNOSIS OR TREATMENT.
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
name: AccessHope
provenance_date: '2026-11-09'
provider_name: AccessHope
provider_slug: accesshope
slug: accesshope-eligibility
source_date: '2026-11-09'
source_filename: accesshope-eligibility.yml
source_heading: Eligibility
source_page: https://www.myaccesshope.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccessHope\naid: accesshope\nurl: https://www.myaccesshope.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not represent or warrant that MyAccessHope is appropriate for use in any particular jurisdiction.\nentity_types:\n- type: individual\n  text: AccessHope makes MyAccessHope and its features, tools and services available to the general public\nrestricted_uses:\n- summary: Not for medical diagnosis or treatment\n  text: NOTHING IN MyAccessHope, WHETHER POSTED BY ACCESSHOPE OR OTHERWISE, IS INTENDED TO BE USED BY YOU OR ANY\n    OTHER PERSON FOR MEDICAL DIAGNOSIS\
  \ OR TREATMENT.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accesshope/eligibility/accesshope-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AccessHope's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Cancer Care
- Employee Benefits
- Health Benefits
- Digital Health
- Telehealth
- Second Opinion
- Employer Health
---
