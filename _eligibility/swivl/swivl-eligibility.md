---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: swivl's Services are available to business customers in the United States and Canada.
  entity_types:
  - text: Our Services are designed for business use only.
    type: business
  - text: To use the Services, you must be at least 18 years of age and authorized to enter into a binding agreement on behalf of the organization you represent.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Communications law compliance
    text: You are solely responsible for complying with all applicable laws governing your use of the Services to communicate with your own customers and tenants
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
name: swivl
provenance_date: '2026-11-10'
provider_name: swivl
provider_slug: swivl
slug: swivl-eligibility
source_date: '2026-11-10'
source_filename: swivl-eligibility.yml
source_heading: Eligibility
source_page: https://www.tryswivl.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: swivl\naid: swivl\nurl: https://www.tryswivl.com/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: swivl's Services are available to business customers in the United States and Canada.\nentity_types:\n- type: business\n  text: Our Services are designed for business use only.\n- type: individual\n  text: To use the Services, you must be at least 18 years of age and authorized to enter into a binding agreement\n    on behalf of the organization you represent.\nrestricted_uses:\n- summary: Communications law compliance\n  text: You are solely responsible for complying\
  \ with all applicable laws governing your use of the Services to\n    communicate with your own customers and tenants\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/swivl/eligibility/swivl-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from swivl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Self Storage
- PropTech
- Artificial Intelligence
- CRM
- Contact Center
- Automation
- Conversational AI
---
