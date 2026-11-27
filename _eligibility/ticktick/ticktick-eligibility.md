---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business, that business accepts these terms. It will hold harmless and indemnify TickTick and its affiliates, officers, agents, and employees from any claim, suit or action arising from or related to the use of the Services or violation of these terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsafe use while mobile
    text: Do not use such Services in a way that distracts you and prevents you from obeying traffic or safety laws.
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
name: TickTick
provenance_date: '2026-11-10'
provider_name: TickTick
provider_slug: ticktick
slug: ticktick-eligibility
source_date: '2026-11-10'
source_filename: ticktick-eligibility.yml
source_heading: Eligibility
source_page: https://ticktick.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TickTick\naid: ticktick\nurl: https://ticktick.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms. It will hold harmless\n    and indemnify TickTick and its affiliates, officers, agents, and employees from any claim, suit or action arising\n    from or related to the use of the Services or violation of these terms\nrestricted_uses:\n- summary: Unsafe use while mobile\n  text: Do not use such Services in a way that distracts you and prevents\
  \ you from obeying traffic or safety laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ticktick/eligibility/ticktick-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from TickTick's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Task Management
- Calendar
- Collaboration
---
