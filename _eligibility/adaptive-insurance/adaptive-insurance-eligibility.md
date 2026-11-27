---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Adaptive is licensed as an insurance producer in the states where Adaptive offers its products and services.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Applications are subject to underwriting guidelines, review, and approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Adaptive Insurance
provenance_date: '2026-11-09'
provider_name: Adaptive Insurance
provider_slug: adaptive-insurance
slug: adaptive-insurance-eligibility
source_date: '2026-11-09'
source_filename: adaptive-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.adaptiveinsurance.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adaptive Insurance\naid: adaptive-insurance\nurl: https://www.adaptiveinsurance.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Adaptive is licensed as an insurance producer in the states where Adaptive offers its products and services.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Applications are subject to underwriting guidelines, review, and approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adaptive-insurance/eligibility/adaptive-insurance-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Adaptive Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Insurtech
- Parametric Insurance
- Specialty Insurance
- Climate Risk
- Weather Data
- Managing General Agent
- Flood
- Power Outage
---
