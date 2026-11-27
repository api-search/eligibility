---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: neither you nor any User is located in, organized under the laws of, or ordinarily resident in any country or region that is subject to U.S. Government sanctions or embargoes
  entity_types:
  - text: You understand and acknowledge that the Services are intended exclusively for commercial and business purposes.
    type: business
  minimum_age:
    text: all Users are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted business categories
    text: your business is not engaged in a restricted category
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: when you create an Account, we may ask you for your name, address, date of birth, and other information that will allow us to identify you.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LiquidTrust
provenance_date: '2026-11-09'
provider_name: LiquidTrust
provider_slug: liquidtrust
slug: liquidtrust-eligibility
source_date: '2026-11-09'
source_filename: liquidtrust-eligibility.yml
source_heading: Eligibility
source_page: https://www.liquidtrust.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiquidTrust\naid: liquidtrust\nurl: https://www.liquidtrust.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: neither you nor any User is located in, organized under the laws of, or ordinarily resident in any country\n    or region that is subject to U.S. Government sanctions or embargoes\nentity_types:\n- type: business\n  text: You understand and acknowledge that the Services are intended exclusively for commercial and business purposes.\nrestricted_uses:\n- summary: Restricted business categories\n  text: your business is not engaged in a restricted\
  \ category\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: when you create an Account, we may ask you for your name, address, date of birth, and other information\n    that will allow us to identify you.\nminimum_age:\n  value: '18'\n  text: all Users are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/liquidtrust/eligibility/liquidtrust-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from LiquidTrust's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- B2B Payments
- Escrow
- Fintech
- Cross-Border Payments
- Marketplace
- Compliance
- KYC
- Trust and Safety
---
