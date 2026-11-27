---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    served: []
    text: 'We make no representation that the Service is appropriate or available for use outside of the United States. Excluded: individuals or entities ordinarily resident in Cuba, Iran, North Korea, Syria, Russia, the Crimea, Donetsk, or Luhansk.'
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are a company or other entity, the individual accepting this Agreement on your behalf represents and warrants that they have authority to bind you to this Agreement.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Businesses on Stripe Prohibited Business List
    text: use the Service to manage or operate (a) businesses included in the Stripe Prohibited Business List
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bonsai
provenance_date: '2026-11-09'
provider_name: Bonsai
provider_slug: bonsai
slug: bonsai-eligibility
source_date: '2026-11-09'
source_filename: bonsai-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellobonsai.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonsai\naid: bonsai\nurl: https://www.hellobonsai.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: 'We make no representation that the Service is appropriate or available for use outside of the United States.\n    Excluded: individuals or entities ordinarily resident in Cuba, Iran, North Korea, Syria, Russia, the Crimea,\n    Donetsk, or Luhansk.'\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are a company or other entity, the individual accepting\
  \ this Agreement on your behalf represents\n    and warrants that they have authority to bind you to this Agreement.\nrestricted_uses:\n- summary: Businesses on Stripe Prohibited Business List\n  text: use the Service to manage or operate (a) businesses included in the Stripe Prohibited Business List\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bonsai/eligibility/bonsai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bonsai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B
- Business Management
- Freelancing
- Agencies
- CRM
- Project Management
- Time Tracking
- Invoicing
- Proposals
- Contracts
- Accounting
- MCP
---
