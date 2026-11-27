---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You warrant that you (as an individual or as a representative of any entity on whose behalf you use the Services) are not located in, or a resident of, any country that is subject to applicable U.S. trade sanctions or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea region of Ukraine).
  entity_types:
  - text: If you are using the Services on behalf of a business, company, or other legal entity, you represent and warrant that you have the legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You shall not access the Services if you are under the age of 18 years old.
    value: '18'
  restricted_uses:
  - summary: High-risk and regulated uses
    text: 'Unless expressly authorized in writing, the Services are not designed for use in:'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sintra
provenance_date: '2026-11-10'
provider_name: Sintra
provider_slug: sintra
slug: sintra-eligibility
source_date: '2026-11-10'
source_filename: sintra-eligibility.yml
source_heading: Eligibility
source_page: https://sintra.ai/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sintra\naid: sintra\nurl: https://sintra.ai/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You warrant that you (as an individual or as a representative of any entity on whose behalf you use the\n    Services) are not located in, or a resident of, any country that is subject to applicable U.S. trade sanctions\n    or embargoes (such as Cuba, Iran, North Korea, Sudan, Syria, or the Crimea region of Ukraine).\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business, company, or other\
  \ legal entity, you represent and\n    warrant that you have the legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: High-risk and regulated uses\n  text: 'Unless expressly authorized in writing, the Services are not designed for use in:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You shall not access the Services if you are under the age of 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/sintra/eligibility/sintra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Sintra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- AI Employees
- Automation
- No-Code
- Productivity
- Customer Service
- Marketing
- Software-as-a-Service
- Small Business
---
