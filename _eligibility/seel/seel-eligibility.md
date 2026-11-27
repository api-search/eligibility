---
api_specs:
- filename: seel-bill-api-openapi.yml
  format: yaml
  label: Seel Bill API
  slug: seel-bill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-bill-api-openapi.yml
- filename: seel-claim-api-openapi.yml
  format: yaml
  label: Seel Claim API
  slug: seel-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-claim-api-openapi.yml
- filename: seel-contract-api-openapi.yml
  format: yaml
  label: Seel Contract API
  slug: seel-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-contract-api-openapi.yml
- filename: seel-event-api-openapi.yml
  format: yaml
  label: Seel Event API
  slug: seel-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-event-api-openapi.yml
- filename: seel-fulfillment-api-openapi.yml
  format: yaml
  label: Seel Fulfillment API
  slug: seel-fulfillment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-fulfillment-api-openapi.yml
- filename: seel-merchant-api-openapi.yml
  format: yaml
  label: Seel Merchant API
  slug: seel-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-merchant-api-openapi.yml
- filename: seel-order-api-openapi.yml
  format: yaml
  label: Seel Order API
  slug: seel-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-order-api-openapi.yml
- filename: seel-product-api-openapi.yml
  format: yaml
  label: Seel Product API
  slug: seel-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-product-api-openapi.yml
- filename: seel-quote-api-openapi.yml
  format: yaml
  label: Seel Quote API
  slug: seel-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seel/openapi/seel-quote-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CN
    - AF
    - IR
    - IQ
    - LY
    - SO
    - SD
    - SY
    - YE
    served: []
    text: Worry-Free Purchase does not cover shipments to, from, or domestically within countries or regions subject to comprehensive U.S. sanctions, including but not limited to, Afghanistan, Iran, Iraq, Libya, Somalia, Sudan, Syria, Yemen, or any other areas subject to OFAC (Office of Foreign Assets Control) restrictions. It also does not cover shipments to or orders placed in mainland China.
  entity_types:
  - text: as a consumer and end customer of a merchant who is contracting with Seel
    type: individual
  - text: If You use the Services for commercial or business purposes, You will not, during the term of these Terms and thereafter for a period of twenty-four (24) months
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use of Services
    text: use the Services, or any portion thereof, for any commercial purpose or for the benefit of any third party or in any manner not permitted by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- AF
- IR
- IQ
- LY
- SO
- SD
- SY
- YE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seel
provenance_date: '2026-11-10'
provider_name: Seel
provider_slug: seel
slug: seel-eligibility
source_date: '2026-11-10'
source_filename: seel-eligibility.yml
source_heading: Eligibility
source_page: https://www.seel.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seel\naid: seel\nurl: https://www.seel.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CN\n  - AF\n  - IR\n  - IQ\n  - LY\n  - SO\n  - SD\n  - SY\n  - YE\n  text: Worry-Free Purchase does not cover shipments to, from, or domestically within countries or regions subject\n    to comprehensive U.S. sanctions, including but not limited to, Afghanistan, Iran, Iraq, Libya, Somalia, Sudan,\n    Syria, Yemen, or any other areas subject to OFAC (Office of Foreign Assets Control) restrictions. It also does\n    not cover shipments to or orders placed in mainland\
  \ China.\nentity_types:\n- type: individual\n  text: as a consumer and end customer of a merchant who is contracting with Seel\n- type: business\n  text: If You use the Services for commercial or business purposes, You will not, during the term of these Terms\n    and thereafter for a period of twenty-four (24) months\nrestricted_uses:\n- summary: No commercial use of Services\n  text: use the Services, or any portion thereof, for any commercial purpose or for the benefit of any third party\n    or in any manner not permitted by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seel/eligibility/seel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Seel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Insurance
- Post-Purchase
- Returns
- Extended Warranty
- Fraud Prevention
- Payments
---
