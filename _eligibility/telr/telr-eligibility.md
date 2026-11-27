---
api_specs:
- filename: telr-agreements-api-openapi.yml
  format: yaml
  label: Telr Agreements API
  slug: telr-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-agreements-api-openapi.yml
- filename: telr-hosted-payment-page-api-openapi.yml
  format: yaml
  label: Telr Hosted Payment Page API
  slug: telr-hosted-payment-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-hosted-payment-page-api-openapi.yml
- filename: telr-payments-api-api-openapi.yml
  format: yaml
  label: Telr Payments API
  slug: telr-payments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-payments-api-api-openapi.yml
- filename: telr-remote-api-openapi.yml
  format: yaml
  label: Telr Remote API
  slug: telr-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-remote-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    - SA
    - JO
    - BH
    text: 'Applicable Market: United Arab Emirates, Kingdom of Saudi Arabia, Bahrain or Jordan; the Agreement applies to merchants operating in these jurisdictions.'
  entity_types:
  - text: only legal entities (including limited liability company and sole proprietorship charitable organization, or persons located and operating in and out of the United Arab Emirates or KSA are eligible to apply for a Telr Account
    type: business
  - text: If you are an individual operating under a sole proprietorship and you are not at least eighteen (18) years old, your Representative must be your parent or legal guardian.
    type: individual
  minimum_age:
    text: If you are under thirteen (13) years old, you may not use the Services under this Agreement.
    value: '13'
  restricted_uses:
  - summary: Peer-to-peer and personal transactions
    text: In no event, Telr Payment Processing Services may be used to conduct personal transactions or peer-to-peer (international or locale remittance) money transmission
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
name: Telr
provenance_date: '2026-11-10'
provider_name: Telr
provider_slug: telr
slug: telr-eligibility
source_date: '2026-11-10'
source_filename: telr-eligibility.yml
source_heading: Eligibility
source_page: https://telr.com/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telr\naid: telr\nurl: https://telr.com/terms-and-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AE\n  - SA\n  - JO\n  - BH\n  excluded: []\n  text: 'Applicable Market: United Arab Emirates, Kingdom of Saudi Arabia, Bahrain or Jordan; the Agreement applies\n    to merchants operating in these jurisdictions.'\nentity_types:\n- type: business\n  text: only legal entities (including limited liability company and sole proprietorship charitable organization,\n    or persons located and operating in and out of the United Arab Emirates or KSA are eligible to apply for a Telr\n   \
  \ Account\n- type: individual\n  text: If you are an individual operating under a sole proprietorship and you are not at least eighteen (18) years\n    old, your Representative must be your parent or legal guardian.\nrestricted_uses:\n- summary: Peer-to-peer and personal transactions\n  text: In no event, Telr Payment Processing Services may be used to conduct personal transactions or peer-to-peer\n    (international or locale remittance) money transmission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under thirteen (13) years old, you may not use the Services under this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/telr/eligibility/telr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Telr's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- United Arab Emirates
---
