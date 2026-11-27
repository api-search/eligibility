---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Customer may only use the Service in the United States, and only for Consumers located in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Credit report data limited to permitted purpose
    text: 'The sole authorized use of Consumer Report Data: to evaluate whether a specific individual Consumer is a suitable contractor or business partner for Customer.'
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
name: Pepper
provenance_date: '2026-11-10'
provider_name: Pepper
provider_slug: pepper
slug: pepper-eligibility
source_date: '2026-11-10'
source_filename: pepper-eligibility.yml
source_heading: Eligibility
source_page: https://www.usepepper.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pepper\naid: pepper\nurl: https://www.usepepper.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Customer may only use the Service in the United States, and only for Consumers located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Credit report data limited to permitted purpose\n  text: 'The sole authorized use of Consumer Report Data: to evaluate whether a specific individual Consumer is\n    a suitable contractor or business partner for Customer.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pepper/eligibility/pepper-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Pepper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application
- Food and Beverage
- Distribution
- Wholesale
- Order Management
- Artificial Intelligence
- ERP Integration
---
