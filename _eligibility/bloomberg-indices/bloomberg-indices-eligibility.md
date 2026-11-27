---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use in locations other than the United States.
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity of your registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bloomberg Indices
provenance_date: '2026-11-09'
provider_name: Bloomberg Indices
provider_slug: bloomberg-indices
slug: bloomberg-indices-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-indices-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Indices\naid: bloomberg-indices\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site\n    and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use\n    in locations other than the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: You may not use the Service for any illegal purpose, for the facilitation of the violation\
  \ of any law or\n    regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-indices/eligibility/bloomberg-indices-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bloomberg Indices's own page on 2026-11-09.
synthetic: false
tags:
- Indices
- Fixed Income
- Equity
- Commodities
- Benchmarks
- Global Aggregate
- Bloomberg
---
