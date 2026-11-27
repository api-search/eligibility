---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply to everyone, including but not limited to, visitors, users, and others who access and use the Website.
    type: individual
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
name: Improovy
provenance_date: '2026-11-09'
provider_name: Improovy
provider_slug: improovy
slug: improovy-eligibility
source_date: '2026-11-09'
source_filename: improovy-eligibility.yml
source_heading: Eligibility
source_page: https://www.improovy.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Improovy\naid: improovy\nurl: https://www.improovy.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms apply to everyone, including but not limited to, visitors, users, and others who access and\n    use the Website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/improovy/eligibility/improovy-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Improovy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Marketplace
- Painting
- PropTech
- Construction
- Consumer
---
