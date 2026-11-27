---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: You must be at least 18 years old to use the Service(s) except in Mississippi, Alabama and Nebraska, where you must be at least the age of majority in the jurisdiction in which you reside.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service(s) except in Mississippi, Alabama and Nebraska, where you must be at least the age of majority in the jurisdiction in which you reside.
    value: '18'
  restricted_uses:
  - summary: No illegal or prohibited content
    text: You may not use the Service(s) for any illegal purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We require the submission of United States state or government issued ID for KYC (Know Your Customer) and AML (Anti-Money Laundering) compliance purposes
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tellus
provenance_date: '2026-11-10'
provider_name: Tellus
provider_slug: tellus
slug: tellus-eligibility
source_date: '2026-11-10'
source_filename: tellus-eligibility.yml
source_heading: Eligibility
source_page: https://www.tellusapp.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tellus\naid: tellus\nurl: https://www.tellusapp.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service(s) except in Mississippi, Alabama and Nebraska, where\n    you must be at least the age of majority in the jurisdiction in which you reside.\nrestricted_uses:\n- summary: No illegal or prohibited content\n  text: You may not use the Service(s) for any illegal purpose.\nverification:\n\
  \  kyc: true\n  kyb: null\n  approval_required: null\n  text: We require the submission of United States state or government issued ID for KYC (Know Your Customer) and\n    AML (Anti-Money Laundering) compliance purposes\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service(s) except in Mississippi, Alabama and Nebraska, where\n    you must be at least the age of majority in the jurisdiction in which you reside.\n"
source_yaml_url: https://artifacts.apis.io/tellus/eligibility/tellus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Tellus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Savings
- Real Estate
- Lending
- Property Management
- Mobile App
- Consumer Finance
---
