---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Delivery Across India
  minimum_age:
    text: According to the Indian Constitution, a person under the age of 18 is minor. Services and facilities offered on our website shall not be available for minors.
    value: '18'
  restricted_uses:
  - summary: Minors barred
    text: Services and facilities offered on our website shall not be available for minors.
  - summary: Persons barred under Indian law
    text: Persons barred under the laws of India are not permitted to use our services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company reserves the end right to reject or grant the access to a new user or terminate the access of existing users, at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wooden Street
provenance_date: '2026-11-10'
provider_name: Wooden Street
provider_slug: wooden-street
slug: wooden-street-eligibility
source_date: '2026-11-10'
source_filename: wooden-street-eligibility.yml
source_heading: Eligibility
source_page: https://www.woodenstreet.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wooden Street\naid: wooden-street\nurl: https://www.woodenstreet.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Delivery Across India\nentity_types: []\nrestricted_uses:\n- summary: Minors barred\n  text: Services and facilities offered on our website shall not be available for minors.\n- summary: Persons barred under Indian law\n  text: Persons barred under the laws of India are not permitted to use our services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company reserves the end right to reject or grant the access to\
  \ a new user or terminate the access of\n    existing users, at any time.\nminimum_age:\n  value: '18'\n  text: According to the Indian Constitution, a person under the age of 18 is minor. Services and facilities offered\n    on our website shall not be available for minors.\n"
source_yaml_url: https://artifacts.apis.io/wooden-street/eligibility/wooden-street-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Wooden Street's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Furniture
- Home Furnishings
- E-Commerce
- Retail
- Direct to Consumer
- Interior Design
- India
---
