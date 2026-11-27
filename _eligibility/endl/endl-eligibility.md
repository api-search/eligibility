---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity ('you')
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorised purpose
    text: (6) you will not use the Services for any illegal or unauthorised purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Identity verification data is processed by our third-party identity verification provider, as described in our Privacy Policy.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Endl
provenance_date: '2026-11-09'
provider_name: Endl
provider_slug: endl
slug: endl-eligibility
source_date: '2026-11-09'
source_filename: endl-eligibility.yml
source_heading: Eligibility
source_page: https://www.endl.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Endl\naid: endl\nurl: https://www.endl.io/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n\
  \    of an entity ('you')\nrestricted_uses:\n- summary: Illegal or unauthorised purpose\n  text: (6) you will not use the Services for any illegal or unauthorised purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Identity verification data is processed by our third-party identity verification provider, as described\n    in our Privacy Policy.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/endl/eligibility/endl-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Endl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Cross-Border Payments
- Treasury
- Banking
- Cards
- Stablecoins
---
