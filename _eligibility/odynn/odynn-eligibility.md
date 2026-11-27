---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Odynn makes no claims that accessing or using or that any of the Services or any of the content is accessible or appropriate outside of the United States.
  entity_types:
  - text: To access and use the Services, the Mobile App, the Site and the other Services, you must be at least 18 years of age.
    type: individual
  minimum_age:
    text: you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Non-competitors only
    text: YOU ARE NOT A COMPETITOR OF ODYNN AND DO NOT INTEND TO USE THE SERVICES, THE MOBILE APP OR ANY OF THE OTHER SERVICES FOR REASONS THAT ARE IN COMPETITION WITH ODYNN
  - summary: Commercial solicitation
    text: Use any of the Services for any commercial solicitation purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: After that, you must register and create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Odynn
provenance_date: '2026-11-10'
provider_name: Odynn
provider_slug: odynn
slug: odynn-eligibility
source_date: '2026-11-10'
source_filename: odynn-eligibility.yml
source_heading: Eligibility
source_page: https://www.odynn.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Odynn\naid: odynn\nurl: https://www.odynn.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Odynn makes no claims that accessing or using or that any of the Services or any of the content is accessible\n    or appropriate outside of the United States.\nentity_types:\n- type: individual\n  text: To access and use the Services, the Mobile App, the Site and the other Services, you must be at least 18\n    years of age.\nrestricted_uses:\n- summary: Non-competitors only\n  text: YOU ARE NOT A COMPETITOR OF ODYNN AND DO NOT INTEND TO USE THE SERVICES, THE MOBILE\
  \ APP OR ANY OF THE OTHER\n    SERVICES FOR REASONS THAT ARE IN COMPETITION WITH ODYNN\n- summary: Commercial solicitation\n  text: Use any of the Services for any commercial solicitation purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: After that, you must register and create an account.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/odynn/eligibility/odynn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Odynn's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Loyalty
- Fintech
- White Label
- SDK
---
