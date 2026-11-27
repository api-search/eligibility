---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Orshot for a company, you confirm you can accept them on its behalf
    type: business
  minimum_age:
    text: You must be at least 18 years old to use Orshot.
    value: '18'
  restricted_uses:
  - summary: No deceptive AI depictions of real people
    text: You must not use AI features to create content that depicts a real person without their consent or that is meant to deceive.
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
name: orshot-com
provenance_date: '2026-11-10'
provider_name: orshot-com
provider_slug: orshot-com
slug: orshot-com-eligibility
source_date: '2026-11-10'
source_filename: orshot-com-eligibility.yml
source_heading: Eligibility
source_page: https://orshot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: orshot-com\naid: orshot-com\nurl: https://orshot.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Orshot for a company, you confirm you can accept them on its behalf\nrestricted_uses:\n- summary: No deceptive AI depictions of real people\n  text: You must not use AI features to create content that depicts a real person without their consent or that\n    is meant to deceive.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\
  \ years old to use Orshot.\n"
source_yaml_url: https://artifacts.apis.io/orshot-com/eligibility/orshot-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from orshot-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Automation
- Artificial Intelligence
---
