---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: individual
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: No automated access
    text: you will not access the Services through automated or non-human means, whether through a bot, script or otherwise
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
name: Evertune
provenance_date: '2026-11-09'
provider_name: Evertune
provider_slug: evertune
slug: evertune-eligibility
source_date: '2026-11-09'
source_filename: evertune-eligibility.yml
source_heading: Eligibility
source_page: https://www.evertune.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evertune\naid: evertune\nurl: https://www.evertune.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: No automated access\n  text: you will not access the Services through automated or non-human means, whether through a bot, script or\n    otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/evertune/eligibility/evertune-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Evertune's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Generative Engine Optimization
- AI Search
- Brand Monitoring
- Marketing Intelligence
- AI Visibility
- Analytics
- Artificial Intelligence
---
