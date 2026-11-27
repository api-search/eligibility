---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Services or Content are appropriate or available for use in locations outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited uses
    text: In any way that violates any applicable federal, state, local, or international law or regulation
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
name: Prax Health
provenance_date: '2026-11-10'
provider_name: Prax Health
provider_slug: prax-health
slug: prax-health-eligibility
source_date: '2026-11-10'
source_filename: prax-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.praxhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prax Health\naid: prax-health\nurl: https://www.praxhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Services or Content are appropriate or available for use in locations\n    outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited uses\n  text: In any way that violates any applicable federal, state, local, or international law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prax-health/eligibility/prax-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Prax Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Nurse Practitioners
- Independent Practice
- Practice Management
- Electronic Health Records
- Medical Billing
- Insurance Credentialing
- Compliance
---
