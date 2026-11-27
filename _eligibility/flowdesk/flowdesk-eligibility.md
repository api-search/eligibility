---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - GB
    served: []
    text: Flowdesk does not directly market to, solicit to, or service retail investors located in the United Kingdom.
  entity_types:
  - text: where you are accessing this Website on behalf of a legal entity, you are duly authorised to act on that entity's behalf and that entity qualifies as an institutional or professional client under applicable law.
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Use violating law
    text: You agree not to use the Website in any way that violates applicable local, national, or international law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flowdesk
provenance_date: '2026-11-09'
provider_name: Flowdesk
provider_slug: flowdesk
slug: flowdesk-eligibility
source_date: '2026-11-09'
source_filename: flowdesk-eligibility.yml
source_heading: Eligibility
source_page: https://www.flowdesk.co/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flowdesk\naid: flowdesk\nurl: https://www.flowdesk.co/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  text: Flowdesk does not directly market to, solicit to, or service retail investors located in the United Kingdom.\nentity_types:\n- type: business\n  text: where you are accessing this Website on behalf of a legal entity, you are duly authorised to act on that\n    entity's behalf and that entity qualifies as an institutional or professional client under applicable law.\nrestricted_uses:\n- summary: Use violating law\n  text: You agree not to use the Website in\
  \ any way that violates applicable local, national, or international law\n    or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/flowdesk/eligibility/flowdesk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Flowdesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- Digital Assets
- Trading
- Liquidity
- Market Maker
- OTC
- WebSocket
---
