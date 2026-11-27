---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally capable of entering into a binding contract to use RealPact. This means you must be at least 18 years old (or the age of majority in your jurisdiction) and have full legal capacity.
    type: individual
  - text: If you are using RealPact on behalf of a real estate brokerage or agency, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: you must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Unauthorized practice of real estate
    text: Use the Service to practice real estate without proper licensing or exceed the scope of your license.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For real estate professionals, you must have valid licensing in your jurisdiction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RealPact
provenance_date: '2026-11-10'
provider_name: RealPact
provider_slug: realpact
slug: realpact-eligibility
source_date: '2026-11-10'
source_filename: realpact-eligibility.yml
source_heading: Eligibility
source_page: https://realpact.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RealPact\naid: realpact\nurl: https://realpact.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally capable of entering into a binding contract to use RealPact. This means you must be\n    at least 18 years old (or the age of majority in your jurisdiction) and have full legal capacity.\n- type: business\n  text: If you are using RealPact on behalf of a real estate brokerage or agency, you represent and warrant that\n    you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary:\
  \ Unauthorized practice of real estate\n  text: Use the Service to practice real estate without proper licensing or exceed the scope of your license.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For real estate professionals, you must have valid licensing in your jurisdiction.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/realpact/eligibility/realpact-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from RealPact's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Artificial Intelligence
- AI Agents
- Automation
- Brokerage
- Transaction Management
- Y Combinator
---
