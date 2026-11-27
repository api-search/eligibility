---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for persons age 18 or older, or minors acting through a parent or legal guardian, who reside in the United States.
  entity_types:
  - text: persons age 18 or older, or minors acting through a parent or legal guardian
    type: individual
  minimum_age:
    text: persons age 18 or older, or minors acting through a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Insurance and medical services limited by state
    text: Insurance products described on the Site are available only in states where Harbor Health Insurance Company is licensed and approved to offer them
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
name: Harbor Health
provenance_date: '2026-11-09'
provider_name: Harbor Health
provider_slug: harbor-health
slug: harbor-health-eligibility
source_date: '2026-11-09'
source_filename: harbor-health-eligibility.yml
source_heading: Eligibility
source_page: https://harborhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harbor Health\naid: harbor-health\nurl: https://harborhealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for persons age 18 or older, or minors acting through a parent or legal guardian, who\n    reside in the United States.\nentity_types:\n- type: individual\n  text: persons age 18 or older, or minors acting through a parent or legal guardian\nrestricted_uses:\n- summary: Insurance and medical services limited by state\n  text: Insurance products described on the Site are available only in states where Harbor Health Insurance Company\n\
  \    is licensed and approved to offer them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: persons age 18 or older, or minors acting through a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/harbor-health/eligibility/harbor-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Harbor Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Primary Care
- Specialty Care
- Value-Based Care
- Payer-Provider
- Texas
---
