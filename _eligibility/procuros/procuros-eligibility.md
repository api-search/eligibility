---
api_specs:
- filename: procuros-all-transactions-api-openapi.yml
  format: yaml
  label: Procuros All Transactions API
  slug: procuros-all-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-all-transactions-api-openapi.yml
- filename: procuros-incoming-transactions-api-openapi.yml
  format: yaml
  label: Procuros Incoming Transactions API
  slug: procuros-incoming-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-incoming-transactions-api-openapi.yml
- filename: procuros-misc-api-openapi.yml
  format: yaml
  label: Procuros Misc API
  slug: procuros-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-misc-api-openapi.yml
- filename: procuros-outgoing-transactions-api-openapi.yml
  format: yaml
  label: Procuros Outgoing Transactions API
  slug: procuros-outgoing-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-outgoing-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing content
    text: The customer undertakes not to store any content on the memory space provided whose provision, publication or use violates applicable law, official requirements or the rights of third parties.
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
name: Procuros
provenance_date: '2026-11-10'
provider_name: Procuros
provider_slug: procuros
slug: procuros-eligibility
source_date: '2026-11-10'
source_filename: procuros-eligibility.yml
source_heading: Eligibility
source_page: https://procuros.io/saas-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Procuros\naid: procuros\nurl: https://procuros.io/saas-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: The customer undertakes not to store any content on the memory space provided whose provision, publication\n    or use violates applicable law, official requirements or the rights of third parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/procuros/eligibility/procuros-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Procuros's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- EDI
- E-Invoicing
- Supply Chain
- Procurement
- B2B Integration
- Logistics
- ERP Integration
---
