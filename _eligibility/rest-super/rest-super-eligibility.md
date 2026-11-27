---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The Site is intended for users within Australia only and products and services referred to on this Site are only available for use in Australia.
  entity_types:
  - text: Access to the AAS EmployerAccess pages on the Site where a password and user name are required (Secure Pages) is only authorised for participating employers of the Retail Employees Superannuation Trust (REST).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'You must not use the Site to: violate any applicable laws or for any purpose that is unlawful'
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
name: Rest Super
provenance_date: '2026-11-10'
provider_name: Rest Super
provider_slug: rest-super
slug: rest-super-eligibility
source_date: '2026-11-10'
source_filename: rest-super-eligibility.yml
source_heading: Eligibility
source_page: https://rest.com.au/why-rest/about-rest/fund-details/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rest Super\naid: rest-super\nurl: https://rest.com.au/why-rest/about-rest/fund-details/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The Site is intended for users within Australia only and products and services referred to on this Site\n    are only available for use in Australia.\nentity_types:\n- type: business\n  text: Access to the AAS EmployerAccess pages on the Site where a password and user name are required (Secure Pages)\n    is only authorised for participating employers of the Retail Employees Superannuation Trust (REST).\nrestricted_uses:\n\
  - summary: Unlawful or harmful use\n  text: 'You must not use the Site to: violate any applicable laws or for any purpose that is unlawful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rest-super/eligibility/rest-super-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Rest Super's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Superannuation
- Financial Services
- Retirement
- Pensions
- Australia
- Investment
---
