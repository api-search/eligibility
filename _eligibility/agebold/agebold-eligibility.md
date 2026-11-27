---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By clicking the "I Agree" button or by otherwise using or registering an account for the Service, you represent that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: The Service is not for persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you will not use the Service for any purpose that is unlawful or prohibited by this Agreement.
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
name: Agebold
provenance_date: '2026-11-09'
provider_name: Agebold
provider_slug: agebold
slug: agebold-eligibility
source_date: '2026-11-09'
source_filename: agebold-eligibility.yml
source_heading: Eligibility
source_page: https://www.agebold.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agebold\naid: agebold\nurl: https://www.agebold.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By clicking the \"I Agree\" button or by otherwise using or registering an account for the Service, you represent\n    that you are at least 18 years of age.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you will not use the Service for any purpose that is unlawful or prohibited by this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: The Service is not for persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/agebold/eligibility/agebold-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Agebold's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Senior Care
- Medicare
- Fitness
- Wellness
- Telehealth
- Healthy Aging
- Fall Prevention
---
