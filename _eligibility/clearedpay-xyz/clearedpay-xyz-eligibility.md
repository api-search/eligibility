---
api_specs:
- filename: clearedpay-xyz-v1-openapi.json
  format: json
  label: Cleared Protocol API V1 API
  slug: cleared-protocol-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearedpay-xyz/openapi/_original/clearedpay-xyz-v1-openapi.json
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not be located in, or a resident of, any jurisdiction where use of the Services would be illegal or prohibited
  entity_types:
  - text: Be at least 18 years of age (or the age of legal majority in your jurisdiction)
    type: individual
  - text: 'If you are using the Services for business purposes, you additionally represent and warrant that: Your business is duly organized and validly existing under applicable law'
    type: business
  minimum_age:
    text: Be at least 18 years of age (or the age of legal majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: Engage in money laundering, terrorist financing, or sanctions evasion
  - summary: Illegal goods or services
    text: Process payments for illegal goods or services
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: 'CLEARED DOES NOT PROVIDE COMPLIANCE SERVICES. We do not: Verify the identity of users or their customers (KYC)'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleared
provenance_date: '2026-11-09'
provider_name: Cleared
provider_slug: clearedpay-xyz
slug: clearedpay-xyz-eligibility
source_date: '2026-11-09'
source_filename: clearedpay-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://clearedpay.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleared\naid: clearedpay-xyz\nurl: https://clearedpay.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not be located in, or a resident of, any jurisdiction where use of the Services would be illegal or prohibited\nentity_types:\n- type: individual\n  text: Be at least 18 years of age (or the age of legal majority in your jurisdiction)\n- type: business\n  text: 'If you are using the Services for business purposes, you additionally represent and warrant that: Your\n    business is duly organized and validly existing under applicable law'\nrestricted_uses:\n- summary: Illegal\
  \ activity\n  text: Engage in money laundering, terrorist financing, or sanctions evasion\n- summary: Illegal goods or services\n  text: Process payments for illegal goods or services\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: 'CLEARED DOES NOT PROVIDE COMPLIANCE SERVICES. We do not: Verify the identity of users or their customers\n    (KYC)'\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age (or the age of legal majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/clearedpay-xyz/eligibility/clearedpay-xyz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Cleared's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- USDC
- Invoicing
- Blockchain
- Contractor
---
