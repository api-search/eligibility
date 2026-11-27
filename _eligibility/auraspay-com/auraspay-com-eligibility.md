---
api_specs:
- filename: auraspay-com-account-api-openapi.yml
  format: yaml
  label: AurasPay Account API
  slug: auraspay-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auraspay-com/openapi/auraspay-com-account-api-openapi.yml
- filename: auraspay-com-agent-checkout-api-openapi.yml
  format: yaml
  label: AurasPay Agent Checkout API
  slug: auraspay-com-agent-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auraspay-com/openapi/auraspay-com-agent-checkout-api-openapi.yml
- filename: auraspay-com-payment-links-api-openapi.yml
  format: yaml
  label: AurasPay Payment Links API
  slug: auraspay-com-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auraspay-com/openapi/auraspay-com-payment-links-api-openapi.yml
- filename: auraspay-com-supported-tokens-api-openapi.yml
  format: yaml
  label: AurasPay Supported Tokens API
  slug: auraspay-com-supported-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auraspay-com/openapi/auraspay-com-supported-tokens-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use Auras Pay only if you are at least 18 years old, have legal capacity to enter into these Terms
    type: individual
  - text: Business users agree that disputes shall be subject to the competent courts of Estonia, unless otherwise required by mandatory law.
    type: business
  minimum_age:
    text: You may use Auras Pay only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited or sanctioned use
    text: are not prohibited from using our services under applicable law, sanctions, or third-party provider restrictions.
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
name: AurasPay
provenance_date: '2026-11-09'
provider_name: AurasPay
provider_slug: auraspay-com
slug: auraspay-com-eligibility
source_date: '2026-11-09'
source_filename: auraspay-com-eligibility.yml
source_heading: Eligibility
source_page: https://auraspay.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AurasPay\naid: auraspay-com\nurl: https://auraspay.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use Auras Pay only if you are at least 18 years old, have legal capacity to enter into these Terms\n- type: business\n  text: Business users agree that disputes shall be subject to the competent courts of Estonia, unless otherwise\n    required by mandatory law.\nrestricted_uses:\n- summary: Prohibited or sanctioned use\n  text: are not prohibited from using our services under applicable law, sanctions, or third-party\
  \ provider restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use Auras Pay only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/auraspay-com/eligibility/auraspay-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AurasPay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Stablecoins
---
