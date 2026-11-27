---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a Registered User must be a single, individual person; each person using our Service must have their own username and password.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use
    text: Commercial use is only permitted pursuant to a separate agreement with AIMR Analytics.
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
name: AdvisorCheck
provenance_date: '2026-11-09'
provider_name: AdvisorCheck
provider_slug: advisorcheck
slug: advisorcheck-eligibility
source_date: '2026-11-09'
source_filename: advisorcheck-eligibility.yml
source_heading: Eligibility
source_page: https://www.advisorcheck.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdvisorCheck\naid: advisorcheck\nurl: https://www.advisorcheck.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a Registered User must be a single, individual person; each person using our Service must have their own\n    username and password.\nrestricted_uses:\n- summary: Commercial use\n  text: Commercial use is only permitted pursuant to a separate agreement with AIMR Analytics.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/advisorcheck/eligibility/advisorcheck-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AdvisorCheck's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Regulatory Data
- Background Checks
- Investor Protection
- Financial Advisors
- Wealth Management
- Consumer Finance
- Compliance
---
