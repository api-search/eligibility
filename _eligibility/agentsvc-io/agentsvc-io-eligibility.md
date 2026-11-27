---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer in the EU, you can withdraw from the purchase of prepaid credit within 14 days
    type: individual
  - text: If you are a merchant, the courts of Hamburg have jurisdiction.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive use
    text: use the services for anything unlawful, including fraud, sanctions evasion, or violating other people's rights
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
name: Agentsvc
provenance_date: '2026-11-09'
provider_name: Agentsvc
provider_slug: agentsvc-io
slug: agentsvc-io-eligibility
source_date: '2026-11-09'
source_filename: agentsvc-io-eligibility.yml
source_heading: Eligibility
source_page: https://agentsvc.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentsvc\naid: agentsvc-io\nurl: https://agentsvc.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer in the EU, you can withdraw from the purchase of prepaid credit within 14 days\n- type: business\n  text: If you are a merchant, the courts of Hamburg have jurisdiction.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: use the services for anything unlawful, including fraud, sanctions evasion, or violating other people's\n    rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentsvc-io/eligibility/agentsvc-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Agentsvc's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Payments
- Web Services
- Agents
---
