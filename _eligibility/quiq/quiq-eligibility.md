---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THIS AGREEMENT.
    type: business
  - text: For U.S. Federal Government users, the Services and Documentation are “Commercial Items”
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: store or transmit infringing, libelous, or otherwise unlawful or tortious material or to store or transmit material in violation of third-party rights;
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
name: Quiq
provenance_date: '2026-11-10'
provider_name: Quiq
provider_slug: quiq
slug: quiq-eligibility
source_date: '2026-11-10'
source_filename: quiq-eligibility.yml
source_heading: Eligibility
source_page: https://quiq.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quiq\naid: quiq\nurl: https://quiq.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THIS AGREEMENT.\n- type: government\n  text: For U.S. Federal Government users, the Services and Documentation are “Commercial Items”\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: store or transmit infringing, libelous, or otherwise unlawful or tortious\
  \ material or to store or transmit\n    material in violation of third-party rights;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quiq/eligibility/quiq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Quiq's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Experience
- Conversational AI
- Contact Center
- Messaging
- Customer Service
- AI Agents
- Chatbots
- Voice AI
---
