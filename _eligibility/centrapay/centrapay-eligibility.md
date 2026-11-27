---
api_specs:
- filename: centrapay-payment-requests-api-openapi.yml
  format: yaml
  label: Centrapay Payment Requests API
  slug: centrapay-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centrapay/openapi/centrapay-payment-requests-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You agree and represent that you are acquiring the Services for the purposes of trade.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Own business use only
    text: You must use the Merchant Account and Services only for your own business and not on behalf of any other person
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We are not obliged to accept all registrations and may decline registrations in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Centrapay
provenance_date: '2026-11-09'
provider_name: Centrapay
provider_slug: centrapay
slug: centrapay-eligibility
source_date: '2026-11-09'
source_filename: centrapay-eligibility.yml
source_heading: Eligibility
source_page: https://www.centrapay.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centrapay\naid: centrapay\nurl: https://www.centrapay.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You agree and represent that you are acquiring the Services for the purposes of trade.\nrestricted_uses:\n- summary: Own business use only\n  text: You must use the Merchant Account and Services only for your own business and not on behalf of any other\n    person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We are not obliged to accept all registrations and may decline registrations\
  \ in our sole discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centrapay/eligibility/centrapay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Centrapay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Digital Wallet
- Open Banking
- QR Code Payments
- Loyalty
- Gift Cards
- Fintech
---
