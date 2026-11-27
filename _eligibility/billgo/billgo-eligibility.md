---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you must maintain a deposit account and Connected Account with a U.S.-based financial institution or provider and a U.S. address. The Services do not support all payment types and will not, for example, process payments that originate outside the U.S.
  entity_types:
  - text: you are a legally organized entity in good standing under the laws of the state in which you were formed
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only commercial payments for own goods/services
    text: you will only use the Services to facilitate receipt of commercial payments and will not use the Services to facilitate receipt of payments that do not relate to the sale of your own goods or services.
  - summary: Prohibited businesses
    text: use the Services for or in support of a prohibited business (as determined by BillGO in its sole discretion)
  - summary: No surcharging
    text: You are prohibited from charging or applying any surcharge, convenience fee, service fee, or similar charge on a transaction or to a Payor
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You agree to provide, upon our request, information about you, your business, your beneficial owners, and your use of the Services that we or our financial institution Partners determine is necessary to comply with applicable anti-money-laundering, sanctions, know-your-customer, or other legal or regulatory requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BillGO
provenance_date: '2026-11-09'
provider_name: BillGO
provider_slug: billgo
slug: billgo-eligibility
source_date: '2026-11-09'
source_filename: billgo-eligibility.yml
source_heading: Eligibility
source_page: https://billgo.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BillGO\naid: billgo\nurl: https://billgo.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you must maintain a deposit account and Connected Account with a U.S.-based financial institution or provider\n    and a U.S. address. The Services do not support all payment types and will not, for example, process payments\n    that originate outside the U.S.\nentity_types:\n- type: business\n  text: you are a legally organized entity in good standing under the laws of the state in which you were formed\nrestricted_uses:\n- summary: Only commercial\
  \ payments for own goods/services\n  text: you will only use the Services to facilitate receipt of commercial payments and will not use the Services\n    to facilitate receipt of payments that do not relate to the sale of your own goods or services.\n- summary: Prohibited businesses\n  text: use the Services for or in support of a prohibited business (as determined by BillGO in its sole discretion)\n- summary: No surcharging\n  text: You are prohibited from charging or applying any surcharge, convenience fee, service fee, or similar charge\n    on a transaction or to a Payor\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You agree to provide, upon our request, information about you, your business, your beneficial owners, and\n    your use of the Services that we or our financial institution Partners determine is necessary to comply with\n    applicable anti-money-laundering, sanctions, know-your-customer, or other legal or regulatory requirements\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billgo/eligibility/billgo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from BillGO's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Bill Pay
- Financial Services
- Banking
- ACH
- Virtual Cards
- Fintech
- GraphQL
---
