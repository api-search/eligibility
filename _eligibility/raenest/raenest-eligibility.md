---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CA
    - NG
    - KE
    - GH
    - UG
    - ZA
    - EG
    text: Only entities organised and registered in the United States, United Kingdom, Canada, Nigeria, Kenya, and Europe are eligible for a business account; only individuals who are legal residents of the United States, Nigeria, Kenya, Ghana Uganda, South Africa, Egypt and the United Kingdom are eligible for a personal account.
  entity_types:
  - text: Only individuals who are legal residents of the United States, Nigeria, Kenya, Ghana Uganda, South Africa, Egypt and the United Kingdom are eligible to apply for a Raenest personal account.
    type: individual
  minimum_age:
    text: You must be an individual and at least 18 years old to use Raenest Service.
    value: '18'
  restricted_uses:
  - summary: Business accounts for business purposes only
    text: The Company and its Entities will use Raenest Account(s) exclusively for business purposes and not for any personal, family, or household use.
  - summary: No access by third parties
    text: Access to the Services or your Raenest Account by third parties is strictly prohibited.
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
name: Raenest
provenance_date: '2026-11-10'
provider_name: Raenest
provider_slug: raenest
slug: raenest-eligibility
source_date: '2026-11-10'
source_filename: raenest-eligibility.yml
source_heading: Eligibility
source_page: https://www.raenest.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raenest\naid: raenest\nurl: https://www.raenest.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - GB\n  - CA\n  - NG\n  - KE\n  - GH\n  - UG\n  - ZA\n  - EG\n  excluded: []\n  text: Only entities organised and registered in the United States, United Kingdom, Canada, Nigeria, Kenya, and\n    Europe are eligible for a business account; only individuals who are legal residents of the United States, Nigeria,\n    Kenya, Ghana Uganda, South Africa, Egypt and the United Kingdom are eligible for a personal account.\nentity_types:\n- type: individual\n  text: Only\
  \ individuals who are legal residents of the United States, Nigeria, Kenya, Ghana Uganda, South Africa,\n    Egypt and the United Kingdom are eligible to apply for a Raenest personal account.\nrestricted_uses:\n- summary: Business accounts for business purposes only\n  text: The Company and its Entities will use Raenest Account(s) exclusively for business purposes and not for any\n    personal, family, or household use.\n- summary: No access by third parties\n  text: Access to the Services or your Raenest Account by third parties is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be an individual and at least 18 years old to use Raenest Service.\n"
source_yaml_url: https://artifacts.apis.io/raenest/eligibility/raenest-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Raenest's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Multi-Currency
- Cross-Border Payments
- Virtual Cards
- Invoicing
- Africa
---
