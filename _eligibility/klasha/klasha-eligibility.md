---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms and using the Services on behalf of a company, business, or organisation, you represent and warrant that you are authorised to do so.
    type: business
  minimum_age:
    text: You have attained the age of 18 years
    value: '18'
  restricted_uses:
  - summary: Restricted business categories
    text: prohibit certain services in line with Schedule 1 of this Agreement (Restricted Business)
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
name: Klasha
provenance_date: '2026-11-09'
provider_name: Klasha
provider_slug: klasha
slug: klasha-eligibility
source_date: '2026-11-09'
source_filename: klasha-eligibility.yml
source_heading: Eligibility
source_page: https://www.klasha.com/legal#terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klasha\naid: klasha\nurl: https://www.klasha.com/legal#terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms and using the Services on behalf of a company, business, or organisation,\n    you represent and warrant that you are authorised to do so.\nrestricted_uses:\n- summary: Restricted business categories\n  text: prohibit certain services in line with Schedule 1 of this Agreement (Restricted Business)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You have attained the age of 18 years\n"
source_yaml_url: https://artifacts.apis.io/klasha/eligibility/klasha-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Klasha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Africa
- Emerging Markets
- Mobile Money
- Payouts
- Foreign Exchange
- Virtual Accounts
- Checkout
- Financial Services
---
