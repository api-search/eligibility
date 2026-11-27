---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Be a legal resident of the United States
  entity_types:
  - text: Be of legal age to form a binding contract with TomoCredit
    type: individual
  - text: You will use the Website only in connection with your business or personal TomoCredit, Inc. Account
    type: business
  minimum_age:
    text: Be of legal age to form a binding contract with TomoCredit
    value: legal age
  restricted_uses:
  - summary: No unlawful or high-risk use of chatbot output
    text: You agree not to use Chatbot responses in connection with any unlawful, fraudulent, or high-risk activity, including but not limited to making credit or lending decisions
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
name: TomoCredit
provenance_date: '2026-11-10'
provider_name: TomoCredit
provider_slug: tomocredit
slug: tomocredit-eligibility
source_date: '2026-11-10'
source_filename: tomocredit-eligibility.yml
source_heading: Eligibility
source_page: https://tomocredit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TomoCredit\naid: tomocredit\nurl: https://tomocredit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Be a legal resident of the United States\nentity_types:\n- type: individual\n  text: Be of legal age to form a binding contract with TomoCredit\n- type: business\n  text: You will use the Website only in connection with your business or personal TomoCredit, Inc. Account\nrestricted_uses:\n- summary: No unlawful or high-risk use of chatbot output\n  text: You agree not to use Chatbot responses in connection with any unlawful, fraudulent, or high-risk\
  \ activity,\n    including but not limited to making credit or lending decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: Be of legal age to form a binding contract with TomoCredit\n"
source_yaml_url: https://artifacts.apis.io/tomocredit/eligibility/tomocredit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TomoCredit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit
- Credit Cards
- Consumer Finance
- Credit Building
---
