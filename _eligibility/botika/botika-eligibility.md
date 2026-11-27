---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable law'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls
    text: Customer is not located or uses, exports, re-exports or imports the Platform (or any portion thereof) in or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls
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
name: Botika
provenance_date: '2026-11-09'
provider_name: Botika
provider_slug: botika
slug: botika-eligibility
source_date: '2026-11-09'
source_filename: botika-eligibility.yml
source_heading: Eligibility
source_page: https://botika.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Botika\naid: botika\nurl: https://botika.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable\n    law'\nrestricted_uses:\n- summary: Export controls\n  text: Customer is not located or uses, exports, re-exports or imports the Platform (or any portion thereof) in\n    or to, any person, entity, organization, jurisdiction or otherwise, in violation of the Export Controls\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/botika/eligibility/botika-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Botika's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Fashion
- E-Commerce
- Photography
- Computer Vision
- Retail
---
