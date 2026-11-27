---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer may be a direct customer or an agency acting on behalf of a client
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: (iii) only use the Services for lawful purposes
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
name: Yieldify *
provenance_date: '2026-11-10'
provider_name: Yieldify *
provider_slug: yieldify
slug: yieldify-eligibility
source_date: '2026-11-10'
source_filename: yieldify-eligibility.yml
source_heading: Eligibility
source_page: https://legal.epsilon.com/us/accelerate-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yieldify *\naid: yieldify\nurl: https://legal.epsilon.com/us/accelerate-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer may be a direct customer or an agency acting on behalf of a client\nrestricted_uses:\n- summary: Lawful purposes only\n  text: (iii) only use the Services for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yieldify/eligibility/yieldify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Yieldify *'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Personalization
- Conversion Rate Optimization
- E-Commerce
- Marketing Technology
- Customer Experience
- A/B Testing
- Tag Management
- Lead Capture
- Website Optimization
---
