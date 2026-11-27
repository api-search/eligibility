---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are 18 (eighteen) years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: Users are responsible for ensuring compliance with applicable laws, regulations and ethical standards when accessing or using the Platform or Services.
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
name: Triomics
provenance_date: '2026-11-10'
provider_name: Triomics
provider_slug: triomics
slug: triomics-eligibility
source_date: '2026-11-10'
source_filename: triomics-eligibility.yml
source_heading: Eligibility
source_page: https://triomics.com/terms-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Triomics\naid: triomics\nurl: https://triomics.com/terms-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: Users are responsible for ensuring compliance with applicable laws, regulations and ethical standards when\n    accessing or using the Platform or Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 (eighteen) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/triomics/eligibility/triomics-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Triomics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Oncology
- Healthcare
- Artificial Intelligence
- Clinical Trials
- Electronic Health Records
- Life Sciences
- Cancer
---
