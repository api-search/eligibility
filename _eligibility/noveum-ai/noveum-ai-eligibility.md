---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services in violation of U.S. export controls or sanctions, and you represent you are not located in an embargoed country or on a restricted-party list.
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract.
    type: individual
  - text: If you are entering into these Terms on behalf of a company, you represent that you have authority to bind that company
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: use the Services as a component of high-risk activities where failure could lead to death, personal injury, or severe damage
  - summary: Regulated data
    text: The Services are not currently designed for, and are not intended to receive, protected health information subject to HIPAA, cardholder data subject to PCI-DSS, or other specially regulated categories of data.
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
name: noveum-ai
provenance_date: '2026-11-10'
provider_name: noveum-ai
provider_slug: noveum-ai
slug: noveum-ai-eligibility
source_date: '2026-11-10'
source_filename: noveum-ai-eligibility.yml
source_heading: Eligibility
source_page: https://noveum.ai/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: noveum-ai\naid: noveum-ai\nurl: https://noveum.ai/en/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services in violation of U.S. export controls or sanctions, and you represent you are\n    not located in an embargoed country or on a restricted-party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract.\n- type: business\n  text: If you are entering into these Terms on behalf of a company, you represent that you have authority to bind\n    that company\nrestricted_uses:\n- summary:\
  \ High-risk activities\n  text: use the Services as a component of high-risk activities where failure could lead to death, personal injury,\n    or severe damage\n- summary: Regulated data\n  text: The Services are not currently designed for, and are not intended to receive, protected health information\n    subject to HIPAA, cardholder data subject to PCI-DSS, or other specially regulated categories of data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/noveum-ai/eligibility/noveum-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from noveum-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Evaluation
- Observability
- Enterprise
---
