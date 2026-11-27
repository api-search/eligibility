---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Application is intended for use within the USA and using the same from a foreign country (outside of the USA) is prohibited.
  minimum_age:
    text: represent that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: Users should not use, disclose, transmit or otherwise process any
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
name: PlanYear
provenance_date: '2026-11-10'
provider_name: PlanYear
provider_slug: planyear
slug: planyear-eligibility
source_date: '2026-11-10'
source_filename: planyear-eligibility.yml
source_heading: Eligibility
source_page: https://planyear.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlanYear\naid: planyear\nurl: https://planyear.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Application is intended for use within the USA and using the same from a foreign country (outside of\n    the USA) is prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Protected health information\n  text: Users should not use, disclose, transmit or otherwise process any\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: represent that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/planyear/eligibility/planyear-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PlanYear's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Benefits
- Insurance
- Platform
- Consulting
---
