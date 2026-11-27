---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 years of age or older to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: You must be 13 years of age or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services
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
name: Comet
provenance_date: '2026-11-09'
provider_name: Comet
provider_slug: comet-browser
slug: comet-browser-eligibility
source_date: '2026-11-09'
source_filename: comet-browser-eligibility.yml
source_heading: Eligibility
source_page: https://www.perplexity.ai/hub/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comet\naid: comet-browser\nurl: https://www.perplexity.ai/hub/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 years of age or older to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be 13 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/comet-browser/eligibility/comet-browser-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Comet's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Browser
- Consumer
- Agents
- Chromium
- Search
- Perplexity
---
