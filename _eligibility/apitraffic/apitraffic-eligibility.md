---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company, you are confirming you may bind that company.
    type: business
  - text: You must be old enough to enter a contract where you live, and not barred from using the service under applicable law.
    type: individual
  minimum_age:
    text: You must be old enough to enter a contract where you live
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
name: ApiTraffic
provenance_date: '2026-11-09'
provider_name: ApiTraffic
provider_slug: apitraffic
slug: apitraffic-eligibility
source_date: '2026-11-09'
source_filename: apitraffic-eligibility.yml
source_heading: Eligibility
source_page: https://www.apitraffic.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApiTraffic\naid: apitraffic\nurl: https://www.apitraffic.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company, you are confirming you may bind that company.\n- type: individual\n  text: You must be old enough to enter a contract where you live, and not barred from using the service under applicable\n    law.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to enter a contract\
  \ where you live\n"
source_yaml_url: https://artifacts.apis.io/apitraffic/eligibility/apitraffic-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from ApiTraffic's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Monitoring
- Observability
- Automation
- Company
---
