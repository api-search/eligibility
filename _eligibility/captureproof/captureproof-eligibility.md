---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Terms apply to both national and international customers except to the extent otherwise noted or as required by applicable law.
  entity_types:
  - text: By accessing or using the services you, the health care provider, medical practice or institution, agree that your credit card will be billed on a monthly basis.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for urgent matters
    text: You agree never to use the Service for urgent matters.
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
name: CaptureProof
provenance_date: '2026-11-09'
provider_name: CaptureProof
provider_slug: captureproof
slug: captureproof-eligibility
source_date: '2026-11-09'
source_filename: captureproof-eligibility.yml
source_heading: Eligibility
source_page: https://captureproof.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaptureProof\naid: captureproof\nurl: https://captureproof.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Terms apply to both national and international customers except to the extent otherwise noted or as\n    required by applicable law.\nentity_types:\n- type: business\n  text: By accessing or using the services you, the health care provider, medical practice or institution, agree\n    that your credit card will be billed on a monthly basis.\nrestricted_uses:\n- summary: Not for urgent matters\n  text: You agree never to use the Service for urgent\
  \ matters.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/captureproof/eligibility/captureproof-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CaptureProof's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Medical Imaging
- Remote Patient Monitoring
- Digital Health
- Artificial Intelligence
- HIPAA
---
