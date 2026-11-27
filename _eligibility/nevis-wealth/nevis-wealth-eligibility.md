---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that you have authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk environments
    text: The Services are not designed or intended for use in high-risk environments or for purposes that would require fail-safe performance
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
name: Nevis Wealth
provenance_date: '2026-11-10'
provider_name: Nevis Wealth
provider_slug: nevis-wealth
slug: nevis-wealth-eligibility
source_date: '2026-11-10'
source_filename: nevis-wealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.neviswealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nevis Wealth\naid: nevis-wealth\nurl: https://www.neviswealth.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that\n    you have authority to bind that entity\nrestricted_uses:\n- summary: High-risk environments\n  text: The Services are not designed or intended for use in high-risk environments or for purposes that would require\n    fail-safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nevis-wealth/eligibility/nevis-wealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nevis Wealth's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Wealth Management
- WealthTech
- Financial Advisors
- Artificial Intelligence
---
