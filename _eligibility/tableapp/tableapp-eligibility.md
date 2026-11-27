---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    text: In order to redeem a TABLEAPP Gift Card, the recipient must activate it by selecting a Restaurant in an available location in the Malaysia.
  minimum_age:
    text: you represent and warrant that you are of legal age and not prohibited by law from accessing or using the Services
    value: null
  restricted_uses:
  - summary: Resale of reservations, memberships, vouchers or gift cards
    text: Resale or attempted resale of TABLEAPP ELITE Membership is prohibited
  - summary: One reservation per meal time
    text: User further agrees not to book more than one (1) reservation for User's personal use during any one meal time
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide true, accurate, current, and complete data about yourself on the TABLEAPP registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TableApp
provenance_date: '2026-11-10'
provider_name: TableApp
provider_slug: tableapp
slug: tableapp-eligibility
source_date: '2026-11-10'
source_filename: tableapp-eligibility.yml
source_heading: Eligibility
source_page: https://www.tableapp.com/info/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TableApp\naid: tableapp\nurl: https://www.tableapp.com/info/agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MY\n  excluded: []\n  text: In order to redeem a TABLEAPP Gift Card, the recipient must activate it by selecting a Restaurant in an\n    available location in the Malaysia.\nentity_types: []\nrestricted_uses:\n- summary: Resale of reservations, memberships, vouchers or gift cards\n  text: Resale or attempted resale of TABLEAPP ELITE Membership is prohibited\n- summary: One reservation per meal time\n  text: User further agrees not to book more than one (1) reservation for User's personal\
  \ use during any one meal\n    time\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide true, accurate, current, and complete data about yourself on the TABLEAPP registration\n    form\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age and not prohibited by law from accessing or using the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/tableapp/eligibility/tableapp-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from TableApp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Reservations
- Restaurant Booking
- Hospitality
- Food and Dining
- Consumer
- Malaysia
---
