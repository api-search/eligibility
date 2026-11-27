---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are not a U.S. resident.
  entity_types:
  - text: You may not use the ZayZoon Services or accept these Terms of Service, if (a) you are not at least 16 years of age
    type: individual
  minimum_age:
    text: you are not at least 16 years of age
    value: '16'
  restricted_uses:
  - summary: Not for prohibited-by-law users
    text: you are prohibited by law from receiving or using the ZayZoon Services
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to allow you to use certain ZayZoon Services, we may be required to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ZayZoon
provenance_date: '2026-11-10'
provider_name: ZayZoon
provider_slug: zayzoon
slug: zayzoon-eligibility
source_date: '2026-11-10'
source_filename: zayzoon-eligibility.yml
source_heading: Eligibility
source_page: https://www.zayzoon.com/usaterms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZayZoon\naid: zayzoon\nurl: https://www.zayzoon.com/usaterms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are not a U.S. resident.\nentity_types:\n- type: individual\n  text: You may not use the ZayZoon Services or accept these Terms of Service, if (a) you are not at least 16 years\n    of age\nrestricted_uses:\n- summary: Not for prohibited-by-law users\n  text: you are prohibited by law from receiving or using the ZayZoon Services\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: In order to allow you to use certain ZayZoon Services, we may\
  \ be required to verify your identity.\nminimum_age:\n  value: '16'\n  text: you are not at least 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/zayzoon/eligibility/zayzoon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ZayZoon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Earned Wage Access
- On-Demand Pay
- Payroll
- Human Resources
- Employee Benefits
- Financial Wellness
- Fintech
- Payments
- Embedded Finance
---
