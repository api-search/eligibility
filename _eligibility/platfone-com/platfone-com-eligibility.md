---
api_specs:
- filename: platfone-com-activation-report-api-openapi.yml
  format: yaml
  label: platfone-com Activation Report API
  slug: platfone-com-activation-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-activation-report-api-openapi.yml
- filename: platfone-com-catalog-api-openapi.yml
  format: yaml
  label: platfone-com Catalog API
  slug: platfone-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-catalog-api-openapi.yml
- filename: platfone-com-prices-api-openapi.yml
  format: yaml
  label: platfone-com Prices API
  slug: platfone-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-prices-api-openapi.yml
- filename: platfone-com-sms-activation-api-openapi.yml
  format: yaml
  label: platfone-com SMS Activation API
  slug: platfone-com-sms-activation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-sms-activation-api-openapi.yml
- filename: platfone-com-user-api-openapi.yml
  format: yaml
  label: platfone-com User API
  slug: platfone-com-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-user-api-openapi.yml
- filename: platfone-com-webhooks-api-openapi.yml
  format: yaml
  label: platfone-com Webhooks 📡 API
  slug: platfone-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    - IR
    - SY
    - KP
    - CU
    served: []
    text: 'Access is prohibited in: Russia, Belarus, Iran, Syria, North Korea, Cuba, Crimea, Donetsk, Luhansk, Zaporizhzhia, Kherson. VPN/proxy circumvention is prohibited.'
  entity_types:
  - text: Partners may use the Platform commercially.
    type: business
  minimum_age:
    text: Platfone is not intended for users under age 18.
    value: '18'
  restricted_uses:
  - summary: Financial, government and security-sensitive services
    text: use numbers for financial, government and other security sensitive services
  - summary: Circumventing security procedures
    text: use numbers to circumvent security procedures on services
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 'KYC becomes mandatory when: usage thresholds for Activation, Retail, or White-Label APIs are exceeded suspicious activity is detected the account is manually flagged'
excluded_countries:
- RU
- BY
- IR
- SY
- KP
- CU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: platfone-com
provenance_date: '2026-11-10'
provider_name: platfone-com
provider_slug: platfone-com
slug: platfone-com-eligibility
source_date: '2026-11-10'
source_filename: platfone-com-eligibility.yml
source_heading: Eligibility
source_page: https://platfone.com/compliance#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: platfone-com\naid: platfone-com\nurl: https://platfone.com/compliance#terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  - IR\n  - SY\n  - KP\n  - CU\n  text: 'Access is prohibited in: Russia, Belarus, Iran, Syria, North Korea, Cuba, Crimea, Donetsk, Luhansk, Zaporizhzhia,\n    Kherson. VPN/proxy circumvention is prohibited.'\nentity_types:\n- type: business\n  text: Partners may use the Platform commercially.\nrestricted_uses:\n- summary: Financial, government and security-sensitive services\n  text: use numbers for financial, government and other security sensitive services\n\
  - summary: Circumventing security procedures\n  text: use numbers to circumvent security procedures on services\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 'KYC becomes mandatory when: usage thresholds for Activation, Retail, or White-Label APIs are exceeded suspicious\n    activity is detected the account is manually flagged'\nminimum_age:\n  value: '18'\n  text: Platfone is not intended for users under age 18.\n"
source_yaml_url: https://artifacts.apis.io/platfone-com/eligibility/platfone-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from platfone-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- SMS
- Temporary-Numbers
---
