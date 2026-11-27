---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Platform is intended for use only by persons located in the United States
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to create an account (“User Account”) and use the Platform.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to create an account
    value: '18'
  restricted_uses:
  - summary: Unauthorized or commercial purposes
    text: Use the Platform for unauthorized or commercial purposes , or for the benefit of any third party, except as expressly permitted by Hazel Health.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you agree to complete any verification steps we may require
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BeMe Health
provenance_date: '2026-11-09'
provider_name: BeMe Health
provider_slug: beme-health
slug: beme-health-eligibility
source_date: '2026-11-09'
source_filename: beme-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.hazel.co/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeMe Health\naid: beme-health\nurl: https://www.hazel.co/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Platform is intended for use only by persons located in the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to create an account (“User\n    Account”) and use the Platform.\nrestricted_uses:\n- summary: Unauthorized or commercial purposes\n  text: Use the Platform for unauthorized or commercial purposes , or for the benefit of any third party, except\n    as expressly\
  \ permitted by Hazel Health.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you agree to complete any verification steps we may require\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to create an account\n"
source_yaml_url: https://artifacts.apis.io/beme-health/eligibility/beme-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BeMe Health's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Telehealth
- K-12
- Education
- Pediatrics
---
