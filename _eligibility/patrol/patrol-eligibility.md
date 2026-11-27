---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any access to, or use of, the Service is limited to individuals who are eighteen (18) years of age or older or otherwise have the ability to form binding contracts in their jurisdiction.
    type: individual
  minimum_age:
    text: limited to individuals who are eighteen (18) years of age or older
    value: '18'
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
name: Patrol
provenance_date: '2026-11-10'
provider_name: Patrol
provider_slug: patrol
slug: patrol-eligibility
source_date: '2026-11-10'
source_filename: patrol-eligibility.yml
source_heading: Eligibility
source_page: https://www.patrolapp.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Patrol\naid: patrol\nurl: https://www.patrolapp.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any access to, or use of, the Service is limited to individuals who are eighteen (18) years of age or older\n    or otherwise have the ability to form binding contracts in their jurisdiction.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: limited to individuals who are eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/patrol/eligibility/patrol-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Patrol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accessibility
- Shopify
- Automation
- Compliance
---
