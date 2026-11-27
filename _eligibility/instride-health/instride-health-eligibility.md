---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are intended for use only within the United States and its territories. We make no representation that the Services are appropriate, or are available for use outside the U.S.
  entity_types:
  - text: You may use the Services only for your own personal, non-commercial use.
    type: individual
  - text: If you are accepting these Terms for another person (“Family Member”) as such Family Member’s parent, guardian, conservator, or custodian, you agree to the terms, conditions, and notices contained or referenced herein on behalf of such Family Member.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use
    text: You will not use the Services or content, or any portion thereof, for any commercial purpose or for the benefit of any third party
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
name: Instride Health
provenance_date: '2026-11-09'
provider_name: Instride Health
provider_slug: instride-health
slug: instride-health-eligibility
source_date: '2026-11-09'
source_filename: instride-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.instride.health/compliance/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instride Health\naid: instride-health\nurl: https://www.instride.health/compliance/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are intended for use only within the United States and its territories. We make no representation\n    that the Services are appropriate, or are available for use outside the U.S.\nentity_types:\n- type: individual\n  text: You may use the Services only for your own personal, non-commercial use.\n- type: other\n  text: If you are accepting these Terms for another person (“Family Member”) as such Family Member’s parent,\
  \ guardian,\n    conservator, or custodian, you agree to the terms, conditions, and notices contained or referenced herein on\n    behalf of such Family Member.\nrestricted_uses:\n- summary: Commercial use\n  text: You will not use the Services or content, or any portion thereof, for any commercial purpose or for the\n    benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/instride-health/eligibility/instride-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Instride Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Mental Health
- Telehealth
- Pediatrics
- Healthcare
- HIPAA
---
