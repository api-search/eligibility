---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing the content from territories where it may be illegal is prohibited.
  entity_types:
  - text: '"Merchant” means a registered user of Arbo arbo Technologies Inc.'
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
name: Arbohq
provenance_date: '2026-11-09'
provider_name: Arbohq
provider_slug: arbohq
slug: arbohq-eligibility
source_date: '2026-11-09'
source_filename: arbohq-eligibility.yml
source_heading: Eligibility
source_page: https://arbohq.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arbohq\naid: arbohq\nurl: https://arbohq.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing the content from territories where it may be illegal is prohibited.\nentity_types:\n- type: business\n  text: '\"Merchant” means a registered user of Arbo arbo Technologies Inc.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arbohq/eligibility/arbohq-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Arbohq's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Regulated
- Platform
- Integration
---
