---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to these Terms of Service
    type: business
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
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
name: Infinitus
provenance_date: '2026-11-09'
provider_name: Infinitus
provider_slug: infinitus
slug: infinitus-eligibility
source_date: '2026-11-09'
source_filename: infinitus-eligibility.yml
source_heading: Eligibility
source_page: https://www.infinitus.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Infinitus\naid: infinitus\nurl: https://www.infinitus.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms of Service on behalf of a company, business or other legal entity,\n    you represent that you have the authority to bind such entity and its affiliates to these Terms of Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service,\
  \ with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/infinitus/eligibility/infinitus-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Infinitus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Voice AI
- Benefit Verification
- Prior Authorization
- HIPAA
---
