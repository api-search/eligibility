---
api_specs:
- filename: bakkt-accounts-api-openapi.yml
  format: yaml
  label: Bakkt Accounts API
  slug: bakkt-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-accounts-api-openapi.yml
- filename: bakkt-authorization-api-openapi.yml
  format: yaml
  label: Bakkt Authorization API
  slug: bakkt-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-authorization-api-openapi.yml
- filename: bakkt-block-trade-allocate-api-openapi.yml
  format: yaml
  label: Bakkt Block Trade & Allocate API
  slug: bakkt-block-trade-allocate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-block-trade-allocate-api-openapi.yml
- filename: bakkt-configuration-and-status-api-openapi.yml
  format: yaml
  label: Bakkt Configuration and Status API
  slug: bakkt-configuration-and-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-configuration-and-status-api-openapi.yml
- filename: bakkt-currency-onboarding-api-openapi.yml
  format: yaml
  label: Bakkt Currency Onboarding API
  slug: bakkt-currency-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-currency-onboarding-api-openapi.yml
- filename: bakkt-documents-api-openapi.yml
  format: yaml
  label: Bakkt Documents API
  slug: bakkt-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-documents-api-openapi.yml
- filename: bakkt-fiat-onboarding-api-openapi.yml
  format: yaml
  label: Bakkt Fiat Onboarding API
  slug: bakkt-fiat-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-fiat-onboarding-api-openapi.yml
- filename: bakkt-gift-api-openapi.yml
  format: yaml
  label: Bakkt Gift API
  slug: bakkt-gift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-gift-api-openapi.yml
- filename: bakkt-instruments-api-openapi.yml
  format: yaml
  label: Bakkt Instruments API
  slug: bakkt-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-instruments-api-openapi.yml
- filename: bakkt-jurisdictions-api-openapi.yml
  format: yaml
  label: Bakkt Jurisdictions API
  slug: bakkt-jurisdictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-jurisdictions-api-openapi.yml
- filename: bakkt-orders-api-openapi.yml
  format: yaml
  label: Bakkt Orders API
  slug: bakkt-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-orders-api-openapi.yml
- filename: bakkt-partner-connectivity-api-openapi.yml
  format: yaml
  label: Bakkt Partner Connectivity API
  slug: bakkt-partner-connectivity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-partner-connectivity-api-openapi.yml
- filename: bakkt-partner-party-funding-api-openapi.yml
  format: yaml
  label: Bakkt Partner Party Funding API
  slug: bakkt-partner-party-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-partner-party-funding-api-openapi.yml
- filename: bakkt-partner-party-kyc-api-openapi.yml
  format: yaml
  label: Bakkt Partner Party Kyc API
  slug: bakkt-partner-party-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-partner-party-kyc-api-openapi.yml
- filename: bakkt-partner-party-linking-api-openapi.yml
  format: yaml
  label: Bakkt Partner Party Linking API
  slug: bakkt-partner-party-linking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-partner-party-linking-api-openapi.yml
- filename: bakkt-positions-api-openapi.yml
  format: yaml
  label: Bakkt Positions API
  slug: bakkt-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-positions-api-openapi.yml
- filename: bakkt-transfers-api-openapi.yml
  format: yaml
  label: Bakkt Transfers API
  slug: bakkt-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bakkt/openapi/bakkt-transfers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may not register an Account or use the Services if you are a resident of, or located in, any state in which Bakkt is not authorized to provide the Services (each, a "Restricted State").
  entity_types:
  - text: To register for an Account or to designate an Authorized User (as defined below), you must be an individual at least eighteen (18) years of age and have the legal capacity to enter into this User Agreement.
    type: individual
  minimum_age:
    text: you must be an individual at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Sanctioned or restricted jurisdictions and persons
    text: You may not register an Account or access or use the Services if you are located or organized in, under the control of, or a citizen or resident of any state, country, territory, or other jurisdiction to which the United States has embargoed the provision of goods or services
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
name: Bakkt
provenance_date: '2026-11-09'
provider_name: Bakkt
provider_slug: bakkt
slug: bakkt-eligibility
source_date: '2026-11-09'
source_filename: bakkt-eligibility.yml
source_heading: Eligibility
source_page: https://bakkt.com/user-agreement-apex-fiat-bakkt-trade/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bakkt\naid: bakkt\nurl: https://bakkt.com/user-agreement-apex-fiat-bakkt-trade/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may not register an Account or use the Services if you are a resident of, or located in, any state in\n    which Bakkt is not authorized to provide the Services (each, a \"Restricted State\").\nentity_types:\n- type: individual\n  text: To register for an Account or to designate an Authorized User (as defined below), you must be an individual\n    at least eighteen (18) years of age and have the legal capacity to enter into this\
  \ User Agreement.\nrestricted_uses:\n- summary: Sanctioned or restricted jurisdictions and persons\n  text: You may not register an Account or access or use the Services if you are located or organized in, under\n    the control of, or a citizen or resident of any state, country, territory, or other jurisdiction to which the\n    United States has embargoed the provision of goods or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be an individual at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/bakkt/eligibility/bakkt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bakkt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Cryptocurrency
- Digital Assets
- Trading
- Payments
- Fiat On-Ramp
- Custody
- Webhook
- FIX Protocol
---
