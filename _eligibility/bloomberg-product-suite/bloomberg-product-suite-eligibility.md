---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use in locations other than the United States.
  entity_types:
  - text: you are at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: The use of your account by any individual under age eighteen (18) is strictly prohibited.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation, or in any manner inconsistent with the TOS.
  - summary: Commercial resale
    text: You agree to use the Service solely for your own noncommercial use and benefit, and not for resale or other transfer or disposition to, or use by or for the benefit of, any other person or entity.
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
name: Bloomberg Product Suite
provenance_date: '2026-11-09'
provider_name: Bloomberg Product Suite
provider_slug: bloomberg-product-suite
slug: bloomberg-product-suite-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-product-suite-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Product Suite\naid: bloomberg-product-suite\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that the Service, including merchandise offered for sale on this site\n    and their copyrights, trademarks, patents, and licensing arrangements, are appropriate or available for use\n    in locations other than the United States.\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old.\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use\
  \ the Service for any illegal purpose, for the facilitation of the violation of any law or\n    regulation, or in any manner inconsistent with the TOS.\n- summary: Commercial resale\n  text: You agree to use the Service solely for your own noncommercial use and benefit, and not for resale or other\n    transfer or disposition to, or use by or for the benefit of, any other person or entity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: The use of your account by any individual under age eighteen (18) is strictly prohibited.\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-product-suite/eligibility/bloomberg-product-suite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bloomberg Product Suite's own page on 2026-11-09.
synthetic: false
tags:
- Product Suite
- Terminal
- Data
- Analytics
- Trading
- Financial Technology
- Bloomberg
---
