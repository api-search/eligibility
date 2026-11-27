---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ANY INDIVIDUAL, PERSON OR ENTITY WHO ACCESSES OR USES
    type: individual
  minimum_age:
    text: you are 18 years of age or older and competent
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You hereby authorize Domuso, either directly or through third parties, to make any inquiries we consider necessary to validate your Account registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Domusoinc
provenance_date: '2026-11-09'
provider_name: Domusoinc
provider_slug: domusoinc
slug: domusoinc-eligibility
source_date: '2026-11-09'
source_filename: domusoinc-eligibility.yml
source_heading: Eligibility
source_page: https://www.domuso.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Domusoinc\naid: domusoinc\nurl: https://www.domuso.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ANY INDIVIDUAL, PERSON OR ENTITY WHO ACCESSES OR USES\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You hereby authorize Domuso, either directly or through third parties, to make any inquiries we consider\n    necessary to validate your Account registration information.\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older and competent\n"
source_yaml_url: https://artifacts.apis.io/domusoinc/eligibility/domusoinc-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Domusoinc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Property Management
- Payments
- Software-as-a-Service
- Real Estate
---
