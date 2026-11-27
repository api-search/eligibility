---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of an entity, you represent that you are authorized to act on behalf of, and bind to this Agreement, such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use limited to customers and evaluation
    text: use the Qbiq System for any purpose other than for its Customers, potential Customers and Evaluation
  - summary: No unlawful or interfering use
    text: use the Qbiq System in a manner that violates any applicable law or third party rights
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
name: Qbiq
provenance_date: '2026-11-10'
provider_name: Qbiq
provider_slug: qbiq
slug: qbiq-eligibility
source_date: '2026-11-10'
source_filename: qbiq-eligibility.yml
source_heading: Eligibility
source_page: https://www.qbiq.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qbiq\naid: qbiq\nurl: https://www.qbiq.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of an entity, you represent that you are authorized to act on behalf of, and\n    bind to this Agreement, such entity.\nrestricted_uses:\n- summary: Use limited to customers and evaluation\n  text: use the Qbiq System for any purpose other than for its Customers, potential Customers and Evaluation\n- summary: No unlawful or interfering use\n  text: use the Qbiq System in a manner that violates any applicable\
  \ law or third party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qbiq/eligibility/qbiq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Qbiq's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Architecture
- Artificial Intelligence
- Space Planning
- Construction
- Visualization
- PropTech
---
