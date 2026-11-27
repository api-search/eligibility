---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you confirm that you are at least 18 years old and legally capable of entering into a binding agreement.
    type: individual
  - text: If you are using the Site on behalf of an organization, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Export control restrictions
    text: 'You represent that you are not: Located in a country subject to U.S. embargo. A denied party under U.S. trade sanctions or export control laws.'
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
name: HavocAI
provenance_date: '2026-11-09'
provider_name: HavocAI
provider_slug: havocai
slug: havocai-eligibility
source_date: '2026-11-09'
source_filename: havocai-eligibility.yml
source_heading: Eligibility
source_page: https://www.havocai.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HavocAI\naid: havocai\nurl: https://www.havocai.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you confirm that you are at least 18 years old and legally capable of entering into a\n    binding agreement.\n- type: business\n  text: If you are using the Site on behalf of an organization, you represent that you have authority to bind that\n    entity.\nrestricted_uses:\n- summary: Export control restrictions\n  text: 'You represent that you are not: Located in a country subject to U.S. embargo.\
  \ A denied party under U.S.\n    trade sanctions or export control laws.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/havocai/eligibility/havocai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HavocAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Defense
- Defense Technology
- Autonomy
- Robotics
- Maritime
- Uncrewed Systems
- Artificial Intelligence
- Command and Control
- Aerospace and Defense
---
