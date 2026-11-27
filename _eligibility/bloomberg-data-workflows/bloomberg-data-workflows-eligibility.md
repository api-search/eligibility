---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use in locations other than the United States.
  entity_types:
  - text: You agree to use the Service solely for your own noncommercial use and benefit
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: No resale or transfer
    text: not for resale or other transfer or disposition to, or use by or for the benefit of, any other person or entity.
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
name: Bloomberg Data Workflows
provenance_date: '2026-11-09'
provider_name: Bloomberg Data Workflows
provider_slug: bloomberg-data-workflows
slug: bloomberg-data-workflows-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-data-workflows-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Data Workflows\naid: bloomberg-data-workflows\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site\n    and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use\n    in locations other than the United States.\nentity_types:\n- type: individual\n  text: You agree to use the Service solely for your own noncommercial use and benefit\nrestricted_uses:\n- summary:\
  \ No resale or transfer\n  text: not for resale or other transfer or disposition to, or use by or for the benefit of, any other person or\n    entity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-data-workflows/eligibility/bloomberg-data-workflows-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bloomberg Data Workflows's own page on 2026-11-09.
synthetic: false
tags:
- Enterprise Data
- Financial Analytics
- Financial Services
- Investment Management
- Market Data
- Reference Data
- Trading
---
