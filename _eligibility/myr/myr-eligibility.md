---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers outside Canada contract with MYR International Inc.; Customers in Canada contract with 9327-3100 Quebec Inc. Customers may not access the Product from any jurisdiction where its provision is prohibited under U.S. or other applicable laws (a “Proscribed Country”).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: use the Products for any use other than Customer’s internal business use
  - summary: Export compliance
    text: Customer agrees not to access the Product from any jurisdiction in which the provision of the Product is prohibited under U.S. or other applicable laws or regulations
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
name: MYR
provenance_date: '2026-11-10'
provider_name: MYR
provider_slug: myr
slug: myr-eligibility
source_date: '2026-11-10'
source_filename: myr-eligibility.yml
source_heading: Eligibility
source_page: https://www.myr.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MYR\naid: myr\nurl: https://www.myr.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customers outside Canada contract with MYR International Inc.; Customers in Canada contract with 9327-3100\n    Quebec Inc. Customers may not access the Product from any jurisdiction where its provision is prohibited under\n    U.S. or other applicable laws (a “Proscribed Country”).\nentity_types: []\nrestricted_uses:\n- summary: Internal business use only\n  text: use the Products for any use other than Customer’s internal business use\n- summary: Export compliance\n  text: Customer\
  \ agrees not to access the Product from any jurisdiction in which the provision of the Product is\n    prohibited under U.S. or other applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/myr/eligibility/myr-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from MYR's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Point-of-Sale
- Restaurant
- Quick Service Restaurant
- Food Service Technology
- Payments
- Loyalty
- Restaurant Management
- Integration
---
