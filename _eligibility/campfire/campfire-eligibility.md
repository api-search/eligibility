---
api_specs:
- filename: campfire-accounts-payable-api-openapi.yml
  format: yaml
  label: Campfire Accounts Payable API
  slug: campfire-accounts-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-accounts-payable-api-openapi.yml
- filename: campfire-accounts-receivable-api-openapi.yml
  format: yaml
  label: Campfire Accounts Receivable API
  slug: campfire-accounts-receivable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-accounts-receivable-api-openapi.yml
- filename: campfire-bank-reconciliation-api-openapi.yml
  format: yaml
  label: Campfire Bank Reconciliation API
  slug: campfire-bank-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-bank-reconciliation-api-openapi.yml
- filename: campfire-cash-management-api-openapi.yml
  format: yaml
  label: Campfire Cash Management API
  slug: campfire-cash-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-cash-management-api-openapi.yml
- filename: campfire-coa-api-openapi.yml
  format: yaml
  label: Campfire Coa API
  slug: campfire-coa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-coa-api-openapi.yml
- filename: campfire-company-objects-api-openapi.yml
  format: yaml
  label: Campfire Company Objects API
  slug: campfire-company-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-company-objects-api-openapi.yml
- filename: campfire-core-accounting-api-openapi.yml
  format: yaml
  label: Campfire Core Accounting API
  slug: campfire-core-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-core-accounting-api-openapi.yml
- filename: campfire-custom-fields-api-openapi.yml
  format: yaml
  label: Campfire Custom Fields API
  slug: campfire-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-custom-fields-api-openapi.yml
- filename: campfire-financial-statements-api-openapi.yml
  format: yaml
  label: Campfire Financial Statements API
  slug: campfire-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-financial-statements-api-openapi.yml
- filename: campfire-integrations-api-openapi.yml
  format: yaml
  label: Campfire Integrations API
  slug: campfire-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-integrations-api-openapi.yml
- filename: campfire-revenue-recognition-api-openapi.yml
  format: yaml
  label: Campfire Revenue Recognition API
  slug: campfire-revenue-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-revenue-recognition-api-openapi.yml
- filename: campfire-settings-api-openapi.yml
  format: yaml
  label: Campfire Settings API
  slug: campfire-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfire/openapi/campfire-settings-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is not designed for minors. You must be at least 18 years of age (or the age of majority in your jurisdiction of residence, if higher) to access or otherwise use the Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction of residence, if higher) to access or otherwise use the Website.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms.
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
name: Campfire
provenance_date: '2026-11-09'
provider_name: Campfire
provider_slug: campfire
slug: campfire-eligibility
source_date: '2026-11-09'
source_filename: campfire-eligibility.yml
source_heading: Eligibility
source_page: https://campfire.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campfire\naid: campfire\nurl: https://campfire.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is not designed for minors. You must be at least 18 years of age (or the age of majority in\n    your jurisdiction of residence, if higher) to access or otherwise use the Website.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction of residence, if higher)\n    to access or otherwise use the Website.\n"
source_yaml_url: https://artifacts.apis.io/campfire/eligibility/campfire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Campfire's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- ERP
- Finance
- Revenue Recognition
- Accounts Payable
- Accounts Receivable
- Artificial Intelligence
---
