---
api_specs:
- filename: fxapis-com-accounts-api-openapi.yml
  format: yaml
  label: fxapis-com Accounts API
  slug: fxapis-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-accounts-api-openapi.yml
- filename: fxapis-com-alerts-api-openapi.yml
  format: yaml
  label: fxapis-com Alerts API
  slug: fxapis-com-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-alerts-api-openapi.yml
- filename: fxapis-com-api-keys-api-openapi.yml
  format: yaml
  label: fxapis-com API keys API
  slug: fxapis-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-api-keys-api-openapi.yml
- filename: fxapis-com-billing-api-openapi.yml
  format: yaml
  label: fxapis-com Billing API
  slug: fxapis-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-billing-api-openapi.yml
- filename: fxapis-com-copy-trading-api-openapi.yml
  format: yaml
  label: fxapis-com Copy trading API
  slug: fxapis-com-copy-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-copy-trading-api-openapi.yml
- filename: fxapis-com-events-api-openapi.yml
  format: yaml
  label: fxapis-com Events API
  slug: fxapis-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-events-api-openapi.yml
- filename: fxapis-com-health-api-openapi.yml
  format: yaml
  label: fxapis-com Health API
  slug: fxapis-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-health-api-openapi.yml
- filename: fxapis-com-history-api-openapi.yml
  format: yaml
  label: fxapis-com History API
  slug: fxapis-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-history-api-openapi.yml
- filename: fxapis-com-instruments-api-openapi.yml
  format: yaml
  label: fxapis-com Instruments API
  slug: fxapis-com-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-instruments-api-openapi.yml
- filename: fxapis-com-lifecycle-api-openapi.yml
  format: yaml
  label: fxapis-com Lifecycle API
  slug: fxapis-com-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-lifecycle-api-openapi.yml
- filename: fxapis-com-market-data-api-openapi.yml
  format: yaml
  label: fxapis-com Market data API
  slug: fxapis-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-market-data-api-openapi.yml
- filename: fxapis-com-members-api-openapi.yml
  format: yaml
  label: fxapis-com Members API
  slug: fxapis-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-members-api-openapi.yml
- filename: fxapis-com-trading-api-openapi.yml
  format: yaml
  label: fxapis-com Trading API
  slug: fxapis-com-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-trading-api-openapi.yml
- filename: fxapis-com-waves-api-openapi.yml
  format: yaml
  label: fxapis-com Waves API
  slug: fxapis-com-waves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-waves-api-openapi.yml
- filename: fxapis-com-webhooks-api-openapi.yml
  format: yaml
  label: fxapis-com Webhooks API
  slug: fxapis-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-webhooks-api-openapi.yml
- filename: fxapis-com-workspace-api-openapi.yml
  format: yaml
  label: fxapis-com Workspace API
  slug: fxapis-com-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fxapis-com/openapi/fxapis-com-workspace-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are subject to sanctions administered by the United Nations, the European Union, the United Kingdom or the United States, or are located in, or ordinarily resident in, a country or territory subject to comprehensive sanctions
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract. Personal is for individuals trading their own accounts.
    type: individual
  - text: Our other plans are intended for businesses and professional developers
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlicensed investment or brokerage business
    text: use the Service to operate an unlicensed investment, portfolio-management, brokerage or money-transmission business
  - summary: Market manipulation and unlawful trading
    text: use the Service for market manipulation, spoofing, layering, wash trading, front-running, abusive latency or price-feed arbitrage
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You create an account with an email address and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: fxapis-com
provenance_date: '2026-11-09'
provider_name: fxapis-com
provider_slug: fxapis-com
slug: fxapis-com-eligibility
source_date: '2026-11-09'
source_filename: fxapis-com-eligibility.yml
source_heading: Eligibility
source_page: https://fxapis.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fxapis-com\naid: fxapis-com\nurl: https://fxapis.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are subject to sanctions administered by the United Nations, the European\n    Union, the United Kingdom or the United States, or are located in, or ordinarily resident in, a country or territory\n    subject to comprehensive sanctions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract. Personal is for individuals trading\n    their own accounts.\n- type: business\n  text:\
  \ Our other plans are intended for businesses and professional developers\nrestricted_uses:\n- summary: Unlicensed investment or brokerage business\n  text: use the Service to operate an unlicensed investment, portfolio-management, brokerage or money-transmission\n    business\n- summary: Market manipulation and unlawful trading\n  text: use the Service for market manipulation, spoofing, layering, wash trading, front-running, abusive latency\n    or price-feed arbitrage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You create an account with an email address and password.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/fxapis-com/eligibility/fxapis-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from fxapis-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Trading
- MT5
- Cloud
---
