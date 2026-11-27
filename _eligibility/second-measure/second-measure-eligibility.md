---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You shall not provide any or all of the Bloomberg Second Measure Services: (i) in any country and/or region with respect to which the United States maintains trade sanctions prohibiting the shipment or provision of services'
  minimum_age:
    text: you (a) have read and agree to be bound by the TOS and (b) are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned or prohibited parties
    text: 'you are not: (i) located in or normally resident of, or the government of, any Sanctioned Jurisdiction'
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
name: Second Measure
provenance_date: '2026-11-10'
provider_name: Second Measure
provider_slug: second-measure
slug: second-measure-eligibility
source_date: '2026-11-10'
source_filename: second-measure-eligibility.yml
source_heading: Eligibility
source_page: https://secondmeasure.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Second Measure\naid: second-measure\nurl: https://secondmeasure.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You shall not provide any or all of the Bloomberg Second Measure Services: (i) in any country and/or region\n    with respect to which the United States maintains trade sanctions prohibiting the shipment or provision of services'\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned or prohibited parties\n  text: 'you are not: (i) located in or normally resident of, or the government of, any Sanctioned Jurisdiction'\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you (a) have read and agree to be bound by the TOS and (b) are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/second-measure/eligibility/second-measure-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Second Measure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Alternative Data
- Analytics
- Consumer Insights
- Financial Data
- Transaction Data
- Bloomberg
---
