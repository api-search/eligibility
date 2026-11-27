---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you may only use the Services if you are resident in a country in which we operate.
  entity_types:
  - text: You must be at least 18 years old to register for an account on the Platform and use the Basic Services.
    type: individual
  - text: You agree not to use the Platform for any commercial, business or re-sale purposes
    type: business
  minimum_age:
    text: You must be at least 18 years old to register for an account on the Platform and use the Basic Services.
    value: '18'
  restricted_uses:
  - summary: Dangerous dog breeds
    text: Dogs covered under the Dangerous Dogs Act 1991, for example pit bull terrier and Japanese tosa, are not permitted to be registered on the Platform.
  - summary: Commercial use and payment for dog care
    text: the prohibition against a Borrower receiving payment from the Owner for dog walking, caring, sitting or other related services
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
name: BorrowMyDoggy
provenance_date: '2026-11-09'
provider_name: BorrowMyDoggy
provider_slug: borrowmydoggy
slug: borrowmydoggy-eligibility
source_date: '2026-11-09'
source_filename: borrowmydoggy-eligibility.yml
source_heading: Eligibility
source_page: https://www.borrowmydoggy.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BorrowMyDoggy\naid: borrowmydoggy\nurl: https://www.borrowmydoggy.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you may only use the Services if you are resident in a country in which we operate.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to register for an account on the Platform and use the Basic Services.\n- type: business\n  text: You agree not to use the Platform for any commercial, business or re-sale purposes\nrestricted_uses:\n- summary: Dangerous dog breeds\n  text: Dogs covered under the Dangerous Dogs Act 1991,\
  \ for example pit bull terrier and Japanese tosa, are not\n    permitted to be registered on the Platform.\n- summary: Commercial use and payment for dog care\n  text: the prohibition against a Borrower receiving payment from the Owner for dog walking, caring, sitting or\n    other related services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for an account on the Platform and use the Basic Services.\n"
source_yaml_url: https://artifacts.apis.io/borrowmydoggy/eligibility/borrowmydoggy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from BorrowMyDoggy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pets
- Dogs
- Marketplace
- Consumer
- Sharing Economy
- Community
- United Kingdom
---
