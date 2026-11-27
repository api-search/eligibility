---
api_specs:
- filename: caliza-beneficiary-v1-api-openapi.yml
  format: yaml
  label: Caliza Beneficiary V1 API
  slug: caliza-beneficiary-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-beneficiary-v1-api-openapi.yml
- filename: caliza-integrator-capabilities-v1-api-openapi.yml
  format: yaml
  label: Caliza Integrator Capabilities V1 API
  slug: caliza-integrator-capabilities-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-integrator-capabilities-v1-api-openapi.yml
- filename: caliza-integrator-v1-api-openapi.yml
  format: yaml
  label: Caliza Integrator V1 API
  slug: caliza-integrator-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-integrator-v1-api-openapi.yml
- filename: caliza-kyc-kyb-v1-api-openapi.yml
  format: yaml
  label: Caliza KYC/KYB V1 API
  slug: caliza-kyc-kyb-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-kyc-kyb-v1-api-openapi.yml
- filename: caliza-payment-v1-api-openapi.yml
  format: yaml
  label: Caliza Payment V1 API
  slug: caliza-payment-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-payment-v1-api-openapi.yml
- filename: caliza-recipient-v1-api-openapi.yml
  format: yaml
  label: Caliza Recipient V1 API
  slug: caliza-recipient-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-recipient-v1-api-openapi.yml
- filename: caliza-related-person-api-openapi.yml
  format: yaml
  label: Caliza Related Person API
  slug: caliza-related-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-related-person-api-openapi.yml
- filename: caliza-terms-and-conditions-v1-api-openapi.yml
  format: yaml
  label: Caliza Terms and Conditions V1 API
  slug: caliza-terms-and-conditions-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-terms-and-conditions-v1-api-openapi.yml
- filename: caliza-transaction-v1-api-openapi.yml
  format: yaml
  label: Caliza Transaction V1 API
  slug: caliza-transaction-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-transaction-v1-api-openapi.yml
- filename: caliza-transaction-v1-sandbox-api-openapi.yml
  format: yaml
  label: Caliza Transaction V1 Sandbox API
  slug: caliza-transaction-v1-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-transaction-v1-sandbox-api-openapi.yml
- filename: caliza-travel-rule-v1-api-openapi.yml
  format: yaml
  label: Caliza Travel Rule V1 API
  slug: caliza-travel-rule-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliza/openapi/caliza-travel-rule-v1-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Website is intended solely for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Users under 18
    text: use of the Site by anyone under 18 is unauthorized and in violation of these Terms of Use.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: If you open a Caliza account and use certain services, federal law requires that we verify some of your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Caliza
provenance_date: '2026-11-09'
provider_name: Caliza
provider_slug: caliza
slug: caliza-eligibility
source_date: '2026-11-09'
source_filename: caliza-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/677ed676bd7257ea423799b4/69177a9c7494e512590531d7_Caliza%20US%20Website%20Terms%20-%2007.17.2025.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caliza\naid: caliza\nurl: https://cdn.prod.website-files.com/677ed676bd7257ea423799b4/69177a9c7494e512590531d7_Caliza%20US%20Website%20Terms%20-%2007.17.2025.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 18\n  text: use of the Site by anyone under 18 is unauthorized and in violation of these Terms of Use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: If you open a Caliza account and use certain services, federal law requires that we verify some of your\n    information.\nminimum_age:\n\
  \  value: '18'\n  text: This Website is intended solely for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/caliza/eligibility/caliza-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Caliza's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Cross-Border Payments
- Stablecoins
- Remittances
- Foreign Exchange
- Virtual Accounts
- Payouts
- KYC
- Latin America
---
