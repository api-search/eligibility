---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services on behalf of a health plan or other organization, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: Our Services are designed for those who are at least 18 years of age although we have offerings available to those under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Non-medical reliance
    text: The Websites is intended for informational purposes only and should not be construed as providing specific medical advice.
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
name: Easyhealth
provenance_date: '2026-11-09'
provider_name: Easyhealth
provider_slug: easyhealth
slug: easyhealth-eligibility
source_date: '2026-11-09'
source_filename: easyhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.easyhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Easyhealth\naid: easyhealth\nurl: https://www.easyhealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of a health plan or other organization, you represent that you\n    have authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Non-medical reliance\n  text: The Websites is intended for informational purposes only and should not be construed as providing specific\n    medical advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services are designed for those who are at least 18 years of age although we have offerings available\n    to those under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/easyhealth/eligibility/easyhealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Easyhealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medicare
- Value-Based Care
- Preventive Care
- Health Insurance
- Care Coordination
- In-Home Care
- Telehealth
- HEDIS
---
