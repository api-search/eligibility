---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is offered primarily to users in the United States
  entity_types:
  - text: You must be at least 18 years old with full legal capacity.
    type: individual
  minimum_age:
    text: You must be at least 18 years old with full legal capacity.
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties or restricted jurisdictions
    text: you may not use it on behalf of any sanctioned party or restricted jurisdiction
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may grant, limit, or revoke access for any account at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 包租公
provenance_date: '2026-11-09'
provider_name: 包租公
provider_slug: baozugong-app
slug: baozugong-app-eligibility
source_date: '2026-11-09'
source_filename: baozugong-app-eligibility.yml
source_heading: Eligibility
source_page: https://baozugong.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 包租公\naid: baozugong-app\nurl: https://baozugong.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is offered primarily to users in the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years old with full legal capacity.\nrestricted_uses:\n- summary: Sanctioned parties or restricted jurisdictions\n  text: you may not use it on behalf of any sanctioned party or restricted jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may grant, limit, or revoke access for any account at our discretion.\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old with full legal capacity.\n"
source_yaml_url: https://artifacts.apis.io/baozugong-app/eligibility/baozugong-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from 包租公's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Investing
- Artificial Intelligence
- Options
- US-Stocks
---
