---
api_specs:
- filename: ppro-authorization-endpoints-api-openapi.yml
  format: yaml
  label: PPRO Authorization Endpoints API
  slug: ppro-authorization-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-authorization-endpoints-api-openapi.yml
- filename: ppro-capture-endpoints-api-openapi.yml
  format: yaml
  label: PPRO Capture Endpoints API
  slug: ppro-capture-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-capture-endpoints-api-openapi.yml
- filename: ppro-dispute-reports-api-openapi.yml
  format: yaml
  label: PPRO Dispute Reports API
  slug: ppro-dispute-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-dispute-reports-api-openapi.yml
- filename: ppro-disputes-api-openapi.yml
  format: yaml
  label: PPRO Disputes API
  slug: ppro-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-disputes-api-openapi.yml
- filename: ppro-enrollment-endpoints-api-openapi.yml
  format: yaml
  label: PPRO Enrollment Endpoints API
  slug: ppro-enrollment-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-enrollment-endpoints-api-openapi.yml
- filename: ppro-internal-api-openapi.yml
  format: yaml
  label: PPRO Internal API
  slug: ppro-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-internal-api-openapi.yml
- filename: ppro-merchants-api-openapi.yml
  format: yaml
  label: PPRO Merchants API
  slug: ppro-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-merchants-api-openapi.yml
- filename: ppro-payment-agreement-revocations-api-openapi.yml
  format: yaml
  label: PPRO Payment Agreement Revocations API
  slug: ppro-payment-agreement-revocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-agreement-revocations-api-openapi.yml
- filename: ppro-payment-agreements-api-openapi.yml
  format: yaml
  label: PPRO Payment Agreements API
  slug: ppro-payment-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-agreements-api-openapi.yml
- filename: ppro-payment-charge-controller-api-openapi.yml
  format: yaml
  label: PPRO Payment Charge Controller API
  slug: ppro-payment-charge-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-charge-controller-api-openapi.yml
- filename: ppro-payment-charges-api-openapi.yml
  format: yaml
  label: PPRO Payment Charges API
  slug: ppro-payment-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-charges-api-openapi.yml
- filename: ppro-payment-instruments-api-openapi.yml
  format: yaml
  label: PPRO Payment Instruments API
  slug: ppro-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-instruments-api-openapi.yml
- filename: ppro-payment-sessions-api-openapi.yml
  format: yaml
  label: PPRO Payment Sessions API
  slug: ppro-payment-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-payment-sessions-api-openapi.yml
- filename: ppro-people-api-openapi.yml
  format: yaml
  label: PPRO People API
  slug: ppro-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-people-api-openapi.yml
- filename: ppro-platforms-api-openapi.yml
  format: yaml
  label: PPRO Platforms API
  slug: ppro-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-platforms-api-openapi.yml
- filename: ppro-psps-api-openapi.yml
  format: yaml
  label: PPRO PS Ps API
  slug: ppro-psps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-psps-api-openapi.yml
- filename: ppro-refund-endpoints-api-openapi.yml
  format: yaml
  label: PPRO Refund Endpoints API
  slug: ppro-refund-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-refund-endpoints-api-openapi.yml
- filename: ppro-void-endpoints-api-openapi.yml
  format: yaml
  label: PPRO Void Endpoints API
  slug: ppro-void-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ppro/openapi/ppro-void-endpoints-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: which, as of the date of these GTCs, comprise Crimea, Cuba, Donetsk Iran, Luhansk, North Korea and Syria.
  entity_types:
  - text: To access the Payment Processing Services, the Contractual Partner must be one of the following types of entities
    type: business
  - text: Under no circumstance will a consumer, a charity or a micro-enterprise as defined in the UK Consumer Duty be accepted as a Contractual Partner
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited industries and business practices
    text: will not permit the Payment Methods to be offered by Merchants or to otherwise be made available for any of the categories of businesses and business practices that are listed in the PPRO Payment Methods – Specific Terms of Use.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: The Contractual Partner’s access to the Payment Processing Services shall be contingent on the successful completion of PPRO’s on-boarding procedures including but not limited to anti-money laundering and customer due diligence verification procedures.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PPRO
provenance_date: '2026-11-10'
provider_name: PPRO
provider_slug: ppro
slug: ppro-eligibility
source_date: '2026-11-10'
source_filename: ppro-eligibility.yml
source_heading: Eligibility
source_page: https://www.ppro.com/legal/payment-services-agreement-general-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PPRO\naid: ppro\nurl: https://www.ppro.com/legal/payment-services-agreement-general-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: which, as of the date of these GTCs, comprise Crimea, Cuba, Donetsk Iran, Luhansk, North Korea and Syria.\nentity_types:\n- type: business\n  text: To access the Payment Processing Services, the Contractual Partner must be one of the following types of\n    entities\n- type: individual\n  text: Under no circumstance will a consumer, a charity or a micro-enterprise as defined in the\
  \ UK Consumer Duty\n    be accepted as a Contractual Partner\nrestricted_uses:\n- summary: Prohibited industries and business practices\n  text: will not permit the Payment Methods to be offered by Merchants or to otherwise be made available for any\n    of the categories of businesses and business practices that are listed in the PPRO Payment Methods – Specific\n    Terms of Use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: The Contractual Partner’s access to the Payment Processing Services shall be contingent on the successful\n    completion of PPRO’s on-boarding procedures including but not limited to anti-money laundering and customer\n    due diligence verification procedures.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ppro/eligibility/ppro-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from PPRO's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Local Payment Methods
- Financial Services
- Fintech
- Acquiring
- Checkout
- E-Commerce
- Digital Wallet
- Recurring Payments
- Disputes
- Chargebacks
- Company
---
