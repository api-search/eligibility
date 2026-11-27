---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Laurence
provenance_date: '2026-11-09'
provider_name: Laurence
provider_slug: laurence
slug: laurence-eligibility
source_date: '2026-11-09'
source_filename: laurence-eligibility.yml
source_heading: Eligibility
source_page: https://www.laurence.com/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laurence\naid: laurence\nurl: https://www.laurence.com/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a company or other legal entity, you represent that you have the\n    authority to bind that entity to this Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/laurence/eligibility/laurence-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Laurence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Amazon
- E-Commerce
- Marketing
- Machine Learning
- Retail Media
- MCP
---
