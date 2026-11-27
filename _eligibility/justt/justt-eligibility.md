---
api_specs:
- filename: justt-chargebacks-api-openapi.yml
  format: yaml
  label: Justt Chargebacks API
  slug: justt-chargebacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-chargebacks-api-openapi.yml
- filename: justt-data-subjects-api-openapi.yml
  format: yaml
  label: Justt Data Subjects API
  slug: justt-data-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-data-subjects-api-openapi.yml
- filename: justt-evidence-api-openapi.yml
  format: yaml
  label: Justt Evidence API
  slug: justt-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-evidence-api-openapi.yml
- filename: justt-files-api-openapi.yml
  format: yaml
  label: Justt Files API
  slug: justt-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-files-api-openapi.yml
- filename: justt-integrations-api-openapi.yml
  format: yaml
  label: Justt Integrations API
  slug: justt-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-integrations-api-openapi.yml
- filename: justt-merchants-api-openapi.yml
  format: yaml
  label: Justt Merchants API
  slug: justt-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-merchants-api-openapi.yml
- filename: justt-pre-chargeback-alerts-api-openapi.yml
  format: yaml
  label: Justt Pre-chargeback Alerts API
  slug: justt-pre-chargeback-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-pre-chargeback-alerts-api-openapi.yml
- filename: justt-sandbox-api-openapi.yml
  format: yaml
  label: Justt Sandbox API
  slug: justt-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-sandbox-api-openapi.yml
- filename: justt-transactions-api-openapi.yml
  format: yaml
  label: Justt Transactions API
  slug: justt-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justt/openapi/justt-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Please note that the Website is only intended for individuals aged eighteen (18) years or older.
    type: individual
  minimum_age:
    text: You must be at least eighteen (18) years of age to create an account.
    value: '18'
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
name: Justt
provenance_date: '2026-11-09'
provider_name: Justt
provider_slug: justt
slug: justt-eligibility
source_date: '2026-11-09'
source_filename: justt-eligibility.yml
source_heading: Eligibility
source_page: https://justt.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Justt\naid: justt\nurl: https://justt.ai/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Please note that the Website is only intended for individuals aged eighteen (18) years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to create an account.\n"
source_yaml_url: https://artifacts.apis.io/justt/eligibility/justt-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Justt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Chargebacks
- Disputes
- Fraud Prevention
- Risk Management
- Financial Services
- E-Commerce
- Artificial Intelligence
- Webhook
---
