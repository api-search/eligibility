---
api_specs:
- filename: fazz-disbursements-api-openapi.yml
  format: yaml
  label: Fazz Disbursements API
  slug: fazz-disbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fazz/openapi/fazz-disbursements-api-openapi.yml
- filename: fazz-payment-methods-api-openapi.yml
  format: yaml
  label: Fazz Payment Methods API
  slug: fazz-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fazz/openapi/fazz-payment-methods-api-openapi.yml
- filename: fazz-payments-api-openapi.yml
  format: yaml
  label: Fazz Payments API
  slug: fazz-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fazz/openapi/fazz-payments-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - SG
    text: Only companies or corporations (as defined in the Companies Act 1967) are eligible to use the Fazz Earn Services. (b) Your company/corporation must be formed or incorporated or existing in Singapore, or in one of the countries in which Earn is supported.
  entity_types:
  - text: Only companies or corporations (as defined in the Companies Act 1967) are eligible to use the Fazz Earn Services.
    type: business
  - text: Pengguna adalah subjek hukum yang cakap dan berwenang menurut ketentuan hukum yang berlaku untuk melakukan perbuatan hukum, termasuk membuat Akun
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Money laundering and illegal transactions
    text: Pembukaan dan/atau penggunaan Rekening tidak dimaksudkan atau dimaksudkan untuk melakukan tindak pidana atau hal-hal yang dilarang berdasarkan peraturan perundang-undangan yang berlaku
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You must complete or have completed the account-opening and account-verification procedures with XFERS PTE. LTD.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fazz
provenance_date: '2026-11-09'
provider_name: Fazz
provider_slug: fazz
slug: fazz-eligibility
source_date: '2026-11-09'
source_filename: fazz-eligibility.yml
source_heading: Eligibility
source_page: https://fazz.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fazz\naid: fazz\nurl: https://fazz.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - SG\n  excluded: []\n  text: Only companies or corporations (as defined in the Companies Act 1967) are eligible to use the Fazz Earn\n    Services. (b) Your company/corporation must be formed or incorporated or existing in Singapore, or in one of\n    the countries in which Earn is supported.\nentity_types:\n- type: business\n  text: Only companies or corporations (as defined in the Companies Act 1967) are eligible to use the Fazz Earn\n    Services.\n- type: individual\n  text:\
  \ Pengguna adalah subjek hukum yang cakap dan berwenang menurut ketentuan hukum yang berlaku untuk melakukan\n    perbuatan hukum, termasuk membuat Akun\nrestricted_uses:\n- summary: Money laundering and illegal transactions\n  text: Pembukaan dan/atau penggunaan Rekening tidak dimaksudkan atau dimaksudkan untuk melakukan tindak pidana\n    atau hal-hal yang dilarang berdasarkan peraturan perundang-undangan yang berlaku\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You must complete or have completed the account-opening and account-verification procedures with XFERS PTE.\n    LTD.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fazz/eligibility/fazz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Fazz's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Payments
- Business Banking
- Disbursements
- Southeast Asia
- PayNow
- Virtual Accounts
---
