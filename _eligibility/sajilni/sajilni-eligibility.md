---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - JO
    - AE
    - SA
    text: Jordan, United Arab Emirates, Saudi Arabia is our country of domicile. Website will NOT deal or provide any services or products to any of OFAC (Office of Foreign Assets Control) sanctions countries
  minimum_age:
    text: you must be at least 18 years of age or, if under the age of 18, you have the consent of your parent or guardian (over the age of 18) to use the Site or register for an account.
    value: '18'
  restricted_uses:
  - summary: No gambling, raffles or prize-based activities
    text: facilitate gambling, gaming, raffles, lotteries, sweepstakes, and/or any other activity featuring the award of a prize
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sajilni
provenance_date: '2026-11-10'
provider_name: Sajilni
provider_slug: sajilni
slug: sajilni-eligibility
source_date: '2026-11-10'
source_filename: sajilni-eligibility.yml
source_heading: Eligibility
source_page: https://business.sajilni.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sajilni\naid: sajilni\nurl: https://business.sajilni.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - JO\n  - AE\n  - SA\n  excluded: []\n  text: Jordan, United Arab Emirates, Saudi Arabia is our country of domicile. Website will NOT deal or provide\n    any services or products to any of OFAC (Office of Foreign Assets Control) sanctions countries\nentity_types: []\nrestricted_uses:\n- summary: No gambling, raffles or prize-based activities\n  text: facilitate gambling, gaming, raffles, lotteries, sweepstakes, and/or any other activity featuring the award\n    of\
  \ a prize\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be required prior to the acknowledgment or completion of any Transaction.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age or, if under the age of 18, you have the consent of your parent or\n    guardian (over the age of 18) to use the Site or register for an account.\n"
source_yaml_url: https://artifacts.apis.io/sajilni/eligibility/sajilni-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sajilni's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Event
- Event Management
- Ticketing
- Event Registration
- Payments
- MENA
- Middle East
---
