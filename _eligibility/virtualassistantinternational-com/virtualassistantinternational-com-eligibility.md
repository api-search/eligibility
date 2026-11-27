---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: VAI does not provide its services in countries, or to persons, where this is not permitted under international sanctions or export restrictions.
  entity_types:
  - text: 'Consumer: a Customer who is a natural person and is not acting in the course of a profession or business.'
    type: individual
  - text: 'Customer: any natural person or legal entity that purchases a Package or creates an account on the Platform.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, misleading or harmful use
    text: (b) use the Platform for unlawful, misleading or harmful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: VAI may, within the limits of the law, verify whether the Customer is able to meet their payment obligations.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: virtualassistantinternational-com
provenance_date: '2026-11-10'
provider_name: virtualassistantinternational-com
provider_slug: virtualassistantinternational-com
slug: virtualassistantinternational-com-eligibility
source_date: '2026-11-10'
source_filename: virtualassistantinternational-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.virtualassistantinternational.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: virtualassistantinternational-com\naid: virtualassistantinternational-com\nurl: https://www.virtualassistantinternational.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: VAI does not provide its services in countries, or to persons, where this is not permitted under international\n    sanctions or export restrictions.\nentity_types:\n- type: individual\n  text: 'Consumer: a Customer who is a natural person and is not acting in the course of a profession or business.'\n- type: business\n  text: 'Customer: any natural person or legal entity that purchases a Package or creates\
  \ an account on the Platform.'\nrestricted_uses:\n- summary: Unlawful, misleading or harmful use\n  text: (b) use the Platform for unlawful, misleading or harmful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: VAI may, within the limits of the law, verify whether the Customer is able to meet their payment obligations.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/virtualassistantinternational-com/eligibility/virtualassistantinternational-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from virtualassistantinternational-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Virtual Assistant
- Remote Work
- Netherlands
---
