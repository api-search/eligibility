---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You reside in the United States and in the state and at the address you have or will provide to us
  entity_types:
  - text: You are at least 18 years of age; You are capable of forming a binding contract with Self
    type: individual
  minimum_age:
    text: You are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or improper activity
    text: You may not use the Services for any illegal, unlawful, malicious or improper activity, as we may determine in our sole discretion.
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
name: Self
provenance_date: '2026-11-10'
provider_name: Self
provider_slug: self
slug: self-eligibility
source_date: '2026-11-10'
source_filename: self-eligibility.yml
source_heading: Eligibility
source_page: https://www.self.inc/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Self\naid: self\nurl: https://www.self.inc/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You reside in the United States and in the state and at the address you have or will provide to us\nentity_types:\n- type: individual\n  text: You are at least 18 years of age; You are capable of forming a binding contract with Self\nrestricted_uses:\n- summary: Illegal or improper activity\n  text: You may not use the Services for any illegal, unlawful, malicious or improper activity, as we may determine\n    in our sole discretion.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/self/eligibility/self-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Self's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Building
- Consumer Finance
- Banking
- Financial Services
- Credit Cards
- Lending
---
