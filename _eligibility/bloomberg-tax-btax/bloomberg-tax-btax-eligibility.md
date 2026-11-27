---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other locations. Information is not intended for distribution to any person in any jurisdiction where contrary to law.
  minimum_age:
    text: The use of your account by any individual under age eighteen (18) is strictly prohibited.
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
name: Bloomberg Tax (BTAX)
provenance_date: '2026-11-09'
provider_name: Bloomberg Tax (BTAX)
provider_slug: bloomberg-tax-btax
slug: bloomberg-tax-btax-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-tax-btax-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Tax (BTAX)\naid: bloomberg-tax-btax\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg makes no representation that materials in this site are appropriate or available for use in other\n    locations. Information is not intended for distribution to any person in any jurisdiction where contrary to\n    law.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or\n    regulation\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: The use of your account by any individual under age eighteen (18) is strictly prohibited.\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-tax-btax/eligibility/bloomberg-tax-btax-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bloomberg Tax (BTAX)'s own page on 2026-11-09.
synthetic: false
tags:
- Tax
- Tax Research
- Tax Compliance
- Tax Planning
- Federal Tax
- International Tax
- Bloomberg Tax
---
