---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: placing an order on behalf of your business and have the necessary authority to do so
    type: business
  minimum_age:
    text: You must be 18 years of age or over to use this Site.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: register by providing the name, address, phone number and contact details of your business in addition to your real name, e-mail address and other required information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MonetaIQ
provenance_date: '2026-11-10'
provider_name: MonetaIQ
provider_slug: monetaiq
slug: monetaiq-eligibility
source_date: '2026-11-10'
source_filename: monetaiq-eligibility.yml
source_heading: Eligibility
source_page: https://monetaiq.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MonetaIQ\naid: monetaiq\nurl: https://monetaiq.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: placing an order on behalf of your business and have the necessary authority to do so\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: register by providing the name, address, phone number and contact details of your business in addition to\n    your real name, e-mail address and other required information\nminimum_age:\n  value: '18'\n  text: You must be 18 years of\
  \ age or over to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/monetaiq/eligibility/monetaiq-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from MonetaIQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Data
- Data Platform
- Analytics
---
