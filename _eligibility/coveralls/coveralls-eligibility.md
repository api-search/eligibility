---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer Personnel means Customer 's employees and each Customer subsidiary's employees, as well as independent contractors providing services to Customer .
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitive analysis (hosted service)
    text: use Coveralls for competitive analysis if the Order is for Hosted Service
  - summary: No publishing performance data
    text: publish data about the performance of Coveralls
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
name: Coveralls
provenance_date: '2026-11-09'
provider_name: Coveralls
provider_slug: coveralls
slug: coveralls-eligibility
source_date: '2026-11-09'
source_filename: coveralls-eligibility.yml
source_heading: Eligibility
source_page: https://coveralls.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coveralls\naid: coveralls\nurl: https://coveralls.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer Personnel means Customer 's employees and each Customer subsidiary's employees, as well as independent\n    contractors providing services to Customer .\nrestricted_uses:\n- summary: No competitive analysis (hosted service)\n  text: use Coveralls for competitive analysis if the Order is for Hosted Service\n- summary: No publishing performance data\n  text: publish data about the performance of Coveralls\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coveralls/eligibility/coveralls-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Coveralls's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Coverage
- CI Integration
- Open Source
- Software-as-a-Service
---
