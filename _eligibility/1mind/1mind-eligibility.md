---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: it is a corporation duly organized and validly existing under the laws of the jurisdiction in which it is incorporated
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal data
    text: not provide 1mind with any Customer Content that is personally identifying information that is classified as sensitive information or otherwise subject to specialized security regimes
  - summary: Unlawful or infringing content
    text: use the Platform to collect, store or transmit infringing, libelous, or otherwise unlawful, or tortious content, material or data
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
name: 1mind
provenance_date: '2026-11-09'
provider_name: 1mind
provider_slug: 1mind
slug: 1mind-eligibility
source_date: '2026-11-09'
source_filename: 1mind-eligibility.yml
source_heading: Eligibility
source_page: https://www.1mind.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1mind\naid: 1mind\nurl: https://www.1mind.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: it is a corporation duly organized and validly existing under the laws of the jurisdiction in which it is\n    incorporated\nrestricted_uses:\n- summary: Sensitive personal data\n  text: not provide 1mind with any Customer Content that is personally identifying information that is classified\n    as sensitive information or otherwise subject to specialized security regimes\n- summary: Unlawful or infringing content\n\
  \  text: use the Platform to collect, store or transmit infringing, libelous, or otherwise unlawful, or tortious\n    content, material or data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/1mind/eligibility/1mind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 1mind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Sales
- Go-To-Market
- Conversational AI
- Sales Enablement
- Revenue Operations
---
