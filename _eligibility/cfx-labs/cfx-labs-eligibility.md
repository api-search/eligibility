---
api_specs:
- filename: cfx-labs-cash-api-openapi.yml
  format: yaml
  label: CFX Labs Cash API
  slug: cfx-labs-cash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-cash-api-openapi.yml
- filename: cfx-labs-deposit-api-openapi.yml
  format: yaml
  label: CFX Labs Deposit API
  slug: cfx-labs-deposit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-deposit-api-openapi.yml
- filename: cfx-labs-deposit-memos-api-openapi.yml
  format: yaml
  label: CFX Labs Deposit Memos API
  slug: cfx-labs-deposit-memos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-deposit-memos-api-openapi.yml
- filename: cfx-labs-escrow-transfers-api-openapi.yml
  format: yaml
  label: CFX Labs Escrow Transfers API
  slug: cfx-labs-escrow-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-escrow-transfers-api-openapi.yml
- filename: cfx-labs-identity-api-openapi.yml
  format: yaml
  label: CFX Labs Identity API
  slug: cfx-labs-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-identity-api-openapi.yml
- filename: cfx-labs-identity-documents-api-openapi.yml
  format: yaml
  label: CFX Labs Identity Documents API
  slug: cfx-labs-identity-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-identity-documents-api-openapi.yml
- filename: cfx-labs-ledger-accounts-api-openapi.yml
  format: yaml
  label: CFX Labs Ledger Accounts API
  slug: cfx-labs-ledger-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-ledger-accounts-api-openapi.yml
- filename: cfx-labs-payment-instruments-api-openapi.yml
  format: yaml
  label: CFX Labs Payment Instruments API
  slug: cfx-labs-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-payment-instruments-api-openapi.yml
- filename: cfx-labs-products-api-openapi.yml
  format: yaml
  label: CFX Labs Products API
  slug: cfx-labs-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-products-api-openapi.yml
- filename: cfx-labs-transfer-requests-api-openapi.yml
  format: yaml
  label: CFX Labs Transfer Requests API
  slug: cfx-labs-transfer-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-transfer-requests-api-openapi.yml
- filename: cfx-labs-us-bank-ach-api-openapi.yml
  format: yaml
  label: CFX Labs US Bank ACH API
  slug: cfx-labs-us-bank-ach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cfx-labs/openapi/cfx-labs-us-bank-ach-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Within the United States, certain products are not available to customers residing in or operating out of NY, CA, or LA.
  entity_types:
  - text: By using this Website, you represent that you are at least the age of majority in your state or province of residence or are visiting this Website under the supervision of a parent or guardian.
    type: individual
  minimum_age:
    text: If you are under the age of sixteen (16), you are not permitted to register as a user or otherwise submit any personal information to CFX.
    value: '16'
  restricted_uses:
  - summary: Access from territories where content is illegal
    text: access to this Website from territories where the content of this Website may be illegal is prohibited.
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
name: CFX Labs
provenance_date: '2026-11-09'
provider_name: CFX Labs
provider_slug: cfx-labs
slug: cfx-labs-eligibility
source_date: '2026-11-09'
source_filename: cfx-labs-eligibility.yml
source_heading: Eligibility
source_page: https://cfx.to/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CFX Labs\naid: cfx-labs\nurl: https://cfx.to/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Within the United States, certain products are not available to customers residing in or operating out of\n    NY, CA, or LA.\nentity_types:\n- type: individual\n  text: By using this Website, you represent that you are at least the age of majority in your state or province\n    of residence or are visiting this Website under the supervision of a parent or guardian.\nrestricted_uses:\n- summary: Access from territories where content is illegal\n  text: access to\
  \ this Website from territories where the content of this Website may be illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under the age of sixteen (16), you are not permitted to register as a user or otherwise submit\n    any personal information to CFX.\n"
source_yaml_url: https://artifacts.apis.io/cfx-labs/eligibility/cfx-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CFX Labs's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Banking
- Payments
- Programmable
- Company
---
