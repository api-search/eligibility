---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: RentSpree makes no representations or warranties that the Platform or Services are appropriate or available for use in locations outside the U.S.
  entity_types:
  - text: If you are accepting these Terms on behalf of a company, organization, or other legal entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: you are over eighteen (18) years old (our Platform and Services are intended solely for use by, and may only be used by individuals eighteen (18) years of age or older)
    value: '18'
  restricted_uses:
  - summary: Fair housing discrimination
    text: You may not use the Platform or Services—or any information obtained through them—to engage in discriminatory practices or otherwise violate any fair housing regulations.
  - summary: Background reports for tenant screening only
    text: are requesting reports solely for tenant screening purposes, (c) will not misuse, resell, or distribute the reports or information in the reports
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
name: RentSpree
provenance_date: '2026-11-10'
provider_name: RentSpree
provider_slug: rentspree
slug: rentspree-eligibility
source_date: '2026-11-10'
source_filename: rentspree-eligibility.yml
source_heading: Eligibility
source_page: https://www.rentspree.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RentSpree\naid: rentspree\nurl: https://www.rentspree.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: RentSpree makes no representations or warranties that the Platform or Services are appropriate or available\n    for use in locations outside the U.S.\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of a company, organization, or other legal entity, you represent\n    and warrant that you have the authority to bind that entity\nrestricted_uses:\n- summary: Fair housing discrimination\n  text: You may not\
  \ use the Platform or Services—or any information obtained through them—to engage in discriminatory\n    practices or otherwise violate any fair housing regulations.\n- summary: Background reports for tenant screening only\n  text: are requesting reports solely for tenant screening purposes, (c) will not misuse, resell, or distribute\n    the reports or information in the reports\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are over eighteen (18) years old (our Platform and Services are intended solely for use by, and may\n    only be used by individuals eighteen (18) years of age or older)\n"
source_yaml_url: https://artifacts.apis.io/rentspree/eligibility/rentspree-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from RentSpree's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Rentals
- Rental Applications
- Tenant Screening
- Credit Check
- Background Checks
- Eviction History
- Income Verification
- Renters Insurance
- Rent Payments
- E-Signature
- Leasing
- Listings
- MLS
- PropTech
- Brokerage
- REALTOR Association
---
