---
api_specs:
- filename: sap-event-mesh-asyncapi.yml
  format: yaml
  label: SAP Event Mesh API
  slug: sap-event-mesh-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sap/asyncapi/sap-event-mesh-asyncapi.yml
- filename: sap-addresses-api-openapi.yml
  format: yaml
  label: SAP Addresses API
  slug: sap-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-addresses-api-openapi.yml
- filename: sap-artifacts-api-openapi.yml
  format: yaml
  label: SAP Artifacts API
  slug: sap-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-artifacts-api-openapi.yml
- filename: sap-authentication-api-openapi.yml
  format: yaml
  label: SAP Authentication API
  slug: sap-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-authentication-api-openapi.yml
- filename: sap-bank-accounts-api-openapi.yml
  format: yaml
  label: SAP Bank Accounts API
  slug: sap-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-bank-accounts-api-openapi.yml
- filename: sap-business-partners-api-openapi.yml
  format: yaml
  label: SAP Business Partners API
  slug: sap-business-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-business-partners-api-openapi.yml
- filename: sap-configurations-api-openapi.yml
  format: yaml
  label: SAP Configurations API
  slug: sap-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-configurations-api-openapi.yml
- filename: sap-deployments-api-openapi.yml
  format: yaml
  label: SAP Deployments API
  slug: sap-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-deployments-api-openapi.yml
- filename: sap-executions-api-openapi.yml
  format: yaml
  label: SAP Executions API
  slug: sap-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-executions-api-openapi.yml
- filename: sap-invoices-api-openapi.yml
  format: yaml
  label: SAP Invoices API
  slug: sap-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-invoices-api-openapi.yml
- filename: sap-items-api-openapi.yml
  format: yaml
  label: SAP Items API
  slug: sap-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-items-api-openapi.yml
- filename: sap-journal-entries-api-openapi.yml
  format: yaml
  label: SAP Journal Entries API
  slug: sap-journal-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-journal-entries-api-openapi.yml
- filename: sap-orders-api-openapi.yml
  format: yaml
  label: SAP Orders API
  slug: sap-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-orders-api-openapi.yml
- filename: sap-roles-api-openapi.yml
  format: yaml
  label: SAP Roles API
  slug: sap-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-roles-api-openapi.yml
- filename: sap-scenarios-api-openapi.yml
  format: yaml
  label: SAP Scenarios API
  slug: sap-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-scenarios-api-openapi.yml
- filename: sap-tax-numbers-api-openapi.yml
  format: yaml
  label: SAP Tax Numbers API
  slug: sap-tax-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap/openapi/sap-tax-numbers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SY
    served: []
    text: SAP Websites may not be accessed or used by any national or certain countries or groups against which the United States and/or European Union have instituted sanctions (including Iran, Cuba, North Korea, Syria, the Crimea Region / Sevastopol
  entity_types:
  - text: Purchasing or licensing of any SAP Software offered on the SAP Store is NOT available for consumers, but solely for merchants/corporations and might require an existing SAP system.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Text and data mining or AI training
    text: including, but not limited, for text and data mining purposes or artificial intelligence training, improvement or evaluation
  - summary: Harvesting personal data of other users
    text: Harvest, collect, or store personal information or data of other users.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SAP
provenance_date: '2026-11-10'
provider_name: SAP
provider_slug: sap
slug: sap-eligibility
source_date: '2026-11-10'
source_filename: sap-eligibility.yml
source_heading: Eligibility
source_page: https://www.sap.com/about/legal/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAP\naid: sap\nurl: https://www.sap.com/about/legal/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SY\n  text: SAP Websites may not be accessed or used by any national or certain countries or groups against which the\n    United States and/or European Union have instituted sanctions (including Iran, Cuba, North Korea, Syria, the\n    Crimea Region / Sevastopol\nentity_types:\n- type: business\n  text: Purchasing or licensing of any SAP Software offered on the SAP Store is NOT available for consumers, but\n    solely for merchants/corporations and\
  \ might require an existing SAP system.\nrestricted_uses:\n- summary: Text and data mining or AI training\n  text: including, but not limited, for text and data mining purposes or artificial intelligence training, improvement\n    or evaluation\n- summary: Harvesting personal data of other users\n  text: Harvest, collect, or store personal information or data of other users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sap/eligibility/sap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SAP's own page on 2026-11-10.
synthetic: false
tags:
- SAP
- Artificial Intelligence
- BTP
- Business Applications
- Cloud
- Data Management
- Enterprise
- ERP
- Integration
- Real-Time
- A2A
---
