---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The patient agrees that they have the authority under the laws of the state or jurisdiction in which they reside to provide this release.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Genomind
provenance_date: '2026-11-09'
provider_name: Genomind
provider_slug: genomind
slug: genomind-eligibility
source_date: '2026-11-09'
source_filename: genomind-eligibility.yml
source_heading: Eligibility
source_page: https://genomind.com/patient-consent-financial-agreement-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Genomind\naid: genomind\nurl: https://genomind.com/patient-consent-financial-agreement-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The patient agrees that they have the authority under the laws of the state or jurisdiction in which they\n    reside to provide this release.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/genomind/eligibility/genomind-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Genomind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Genomics
- Pharmacogenomics
- Precision Medicine
- Mental Health
- Diagnostics
- Laboratory
- Clinical Decision Support
- HIPAA
- EHR Integration
---
