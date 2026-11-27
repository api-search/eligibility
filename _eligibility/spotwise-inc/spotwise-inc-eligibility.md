---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for commercial use by businesses and professionals.
    type: business
  - text: These Terms apply to all visitors, users, and others who access or use the Service, whether as an individual or as a representative of a business entity.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years of age and have the legal capacity to enter into binding contracts under applicable law.
    value: '18'
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
name: Spotwise
provenance_date: '2026-11-10'
provider_name: Spotwise
provider_slug: spotwise-inc
slug: spotwise-inc-eligibility
source_date: '2026-11-10'
source_filename: spotwise-inc-eligibility.yml
source_heading: Eligibility
source_page: https://spotwise.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spotwise\naid: spotwise-inc\nurl: https://spotwise.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for commercial use by businesses and professionals.\n- type: individual\n  text: These Terms apply to all visitors, users, and others who access or use the Service, whether as an individual\n    or as a representative of a business entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that\
  \ you are at least 18 years of age and have the legal capacity to enter into binding contracts\n    under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/spotwise-inc/eligibility/spotwise-inc-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Spotwise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Broadcast Media
- Advertising
- Media Monitoring
- Sales Intelligence
- Lead Generation
- Artificial Intelligence
- Radio
- MCP
- Agents
- Attribution
---
