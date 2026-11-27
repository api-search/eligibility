---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Gyft is based in the United States and our Services are subject to U.S. law. We make no representations or warranties that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: Our Services are intended solely for users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or unauthorized use
    text: Use the Services for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Services, you will be required to register for an account with Gyft.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gyft
provenance_date: '2026-11-09'
provider_name: Gyft
provider_slug: gyft
slug: gyft-eligibility
source_date: '2026-11-09'
source_filename: gyft-eligibility.yml
source_heading: Eligibility
source_page: https://www.gyft.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gyft\naid: gyft\nurl: https://www.gyft.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Gyft is based in the United States and our Services are subject to U.S. law. We make no representations\n    or warranties that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: Our Services are intended solely for users who are 13 years of age or older.\nrestricted_uses:\n- summary: No illegal or unauthorized use\n  text: Use the Services for any illegal or unauthorized purpose\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: In order to use the Services, you will be required to register for an account with Gyft.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gyft/eligibility/gyft-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Gyft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gift Cards
- Digital Gift Cards
- Payments
- Rewards
- Incentives
- Fintech
- E-Commerce
---
