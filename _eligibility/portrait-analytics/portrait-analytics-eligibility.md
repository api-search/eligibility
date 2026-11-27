---
api_specs:
- filename: portrait-analytics-openapi-generated.yml
  format: yaml
  label: Portrait Analytics API
  slug: portrait-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/portrait-analytics/openapi/_ae-authored/portrait-analytics-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: SERVICES AND INFORMATION INTENDED FOR USERS OF THE SITE ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: illegal activity
    text: You may not use this Site or Materials to solicit the performance of any illegal activity or other activity which infringes the rights of Company or others.
  - summary: export law violations
    text: You may not use or export or re-export any Materials or any copy or adaptation of such Materials, or any product or service offered on the Site, in violation of any applicable laws or regulations
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
name: Portrait Analytics
provenance_date: '2026-11-10'
provider_name: Portrait Analytics
provider_slug: portrait-analytics
slug: portrait-analytics-eligibility
source_date: '2026-11-10'
source_filename: portrait-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://portraitresearch.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Portrait Analytics\naid: portrait-analytics\nurl: https://portraitresearch.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: illegal activity\n  text: You may not use this Site or Materials to solicit the performance of any illegal activity or other activity\n    which infringes the rights of Company or others.\n- summary: export law violations\n  text: You may not use or export or re-export any Materials or any copy or adaptation of such Materials, or any\n    product or service offered on the Site, in violation\
  \ of any applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: SERVICES AND INFORMATION INTENDED FOR USERS OF THE SITE ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/portrait-analytics/eligibility/portrait-analytics-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Portrait Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Finance
- Research
- Investment
- Data
---
