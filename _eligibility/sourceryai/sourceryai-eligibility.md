---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are not intended for individuals under 13 years of age. If you are under 13 years of age you are prohibitted from using the services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: Your use of the Services, including but not limited to any software you develop using Sourcery, must be and shall be in accordance with any and all laws and regulations that apply to you and your use of the Services.
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
name: Sourcery.AI
provenance_date: '2026-11-10'
provider_name: Sourcery.AI
provider_slug: sourceryai
slug: sourceryai-eligibility
source_date: '2026-11-10'
source_filename: sourceryai-eligibility.yml
source_heading: Eligibility
source_page: https://www.sourcery.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sourcery.AI\naid: sourceryai\nurl: https://www.sourcery.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are not intended for individuals under 13 years of age. If you are under 13 years of age you\n    are prohibitted from using the services.\nrestricted_uses:\n- summary: Compliance with laws\n  text: Your use of the Services, including but not limited to any software you develop using Sourcery, must be\n    and shall be in accordance with any and all laws and regulations that apply to you and your use of the\
  \ Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sourceryai/eligibility/sourceryai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sourcery.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Review
- Developer Tools
- Static Analysis
- Security Scanning
- Code Quality
- Artificial Intelligence
- DevOps
---
