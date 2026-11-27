---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Registration or subscription to the Services and payment of any applicable fee, authorizes a single individual to use the Services unless otherwise expressly stated.
    type: individual
  - text: The Services may be used only by you (i) for your internal business purposes and only for your direct benefit
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Heavily regulated industry services
    text: If you use the Services to provide any services in any heavily regulated industry, such as, without limitation, medical, legal, tax or financial services or advice, you are fully responsible for all such services
  - summary: No use on behalf of third parties
    text: use the Services on behalf of any third-party or for any purpose other than as described in these Terms of Use
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
name: EarnUp
provenance_date: '2026-11-09'
provider_name: EarnUp
provider_slug: earnup
slug: earnup-eligibility
source_date: '2026-11-09'
source_filename: earnup-eligibility.yml
source_heading: Eligibility
source_page: https://earnup.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EarnUp\naid: earnup\nurl: https://earnup.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Registration or subscription to the Services and payment of any applicable fee, authorizes a single individual\n    to use the Services unless otherwise expressly stated.\n- type: business\n  text: The Services may be used only by you (i) for your internal business purposes and only for your direct benefit\nrestricted_uses:\n- summary: Heavily regulated industry services\n  text: If you use the Services to provide\
  \ any services in any heavily regulated industry, such as, without limitation,\n    medical, legal, tax or financial services or advice, you are fully responsible for all such services\n- summary: No use on behalf of third parties\n  text: use the Services on behalf of any third-party or for any purpose other than as described in these Terms\n    of Use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/earnup/eligibility/earnup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from EarnUp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Debt Repayment
- Personal Finance
- Payments
- Financial Wellness
- Lending
---
