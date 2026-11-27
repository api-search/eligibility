---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Sensitive data
    text: Customer may not submit any Customer Content that includes a social security number, passport number, driver’s license number, or similar identifier, credit card or debit card number
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
name: CloudTrucks
provenance_date: '2026-11-09'
provider_name: CloudTrucks
provider_slug: cloudtrucks
slug: cloudtrucks-eligibility
source_date: '2026-11-09'
source_filename: cloudtrucks-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudtrucks.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudTrucks\naid: cloudtrucks\nurl: https://www.cloudtrucks.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive data\n  text: Customer may not submit any Customer Content that includes a social security number, passport number, driver’s\n    license number, or similar identifier, credit card or debit card number\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for and should not be used by anyone\
  \ under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/cloudtrucks/eligibility/cloudtrucks-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CloudTrucks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Trucking
- Freight
- Logistics
- Transportation
- Supply Chain
- Fleet Management
- Mobile App
---
