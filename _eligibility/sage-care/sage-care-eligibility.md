---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You further represent and warrant that you are at least eighteen years of age and lawfully reside in the United States.
  minimum_age:
    text: you are at least eighteen years of age and lawfully reside in the United States
    value: '18'
  restricted_uses:
  - summary: Competitor benefit
    text: use the Site or the Services to in any way assist or benefit a competitor of Sage
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You authorize Sage to take whatever steps it deems necessary, in its sole discretion, to verify the accuracy of your representations and warranties.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sage Care
provenance_date: '2026-11-10'
provider_name: Sage Care
provider_slug: sage-care
slug: sage-care-eligibility
source_date: '2026-11-10'
source_filename: sage-care-eligibility.yml
source_heading: Eligibility
source_page: https://www.sagecare.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sage Care\naid: sage-care\nurl: https://www.sagecare.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You further represent and warrant that you are at least eighteen years of age and lawfully reside in the\n    United States.\nentity_types: []\nrestricted_uses:\n- summary: Competitor benefit\n  text: use the Site or the Services to in any way assist or benefit a competitor of Sage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You authorize Sage to take whatever steps it deems necessary, in its sole discretion, to verify the\
  \ accuracy\n    of your representations and warranties.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen years of age and lawfully reside in the United States\n"
source_yaml_url: https://artifacts.apis.io/sage-care/eligibility/sage-care-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sage Care's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Artificial Intelligence
- CRM
- HIPAA
- Health Assurance
---
