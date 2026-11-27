---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least eighteen (18) years old and able to form a binding contract.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: The Services are not intended for, and may not be used by, anyone under eighteen (18).
    value: '18'
  restricted_uses:
  - summary: Sensitive data in AI Features
    text: You will not submit government-issued identifiers, financial account numbers, health information, biometric identifiers, or other sensitive personal information to the AI Features, except where the Services are configured to receive that information
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
name: Pave
provenance_date: '2026-11-10'
provider_name: Pave
provider_slug: pave
slug: pave-eligibility
source_date: '2026-11-10'
source_filename: pave-eligibility.yml
source_heading: Eligibility
source_page: https://www.pave.com/company/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pave\naid: pave\nurl: https://www.pave.com/company/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least eighteen (18) years old and able to form a binding contract.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Sensitive data in AI Features\n  text: You will not submit\
  \ government-issued identifiers, financial account numbers, health information, biometric\n    identifiers, or other sensitive personal information to the AI Features, except where the Services are configured\n    to receive that information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for, and may not be used by, anyone under eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/pave/eligibility/pave-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compensation
- Human Resources
- Compensation Benchmarking
- Market Data
- People Analytics
- Total Rewards
---
