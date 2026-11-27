---
api_specs:
- filename: intely-apps-api-openapi.yml
  format: yaml
  label: Intely Apps API
  slug: intely-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-apps-api-openapi.yml
- filename: intely-connect-api-openapi.yml
  format: yaml
  label: Intely Connect API
  slug: intely-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-connect-api-openapi.yml
- filename: intely-data-processor-api-openapi.yml
  format: yaml
  label: Intely Data Processor API
  slug: intely-data-processor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-data-processor-api-openapi.yml
- filename: intely-forms-api-openapi.yml
  format: yaml
  label: Intely Forms API
  slug: intely-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-forms-api-openapi.yml
- filename: intely-identity-management-api-openapi.yml
  format: yaml
  label: Intely Identity Management API
  slug: intely-identity-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-identity-management-api-openapi.yml
- filename: intely-rosetta-api-openapi.yml
  format: yaml
  label: Intely Rosetta API
  slug: intely-rosetta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-rosetta-api-openapi.yml
- filename: intely-storage-api-openapi.yml
  format: yaml
  label: Intely Storage API
  slug: intely-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-storage-api-openapi.yml
- filename: intely-webhooks-api-openapi.yml
  format: yaml
  label: Intely Webhooks API
  slug: intely-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intely/openapi/intely-webhooks-api-openapi.yml
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
  - summary: Export control and bribery compliance
    text: Customer represents, covenants, and warrants that Customer will comply with all applicable export control, bribery, and other laws and regulations.
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
name: Intely
provenance_date: '2026-11-09'
provider_name: Intely
provider_slug: intely
slug: intely-eligibility
source_date: '2026-11-09'
source_filename: intely-eligibility.yml
source_heading: Eligibility
source_page: https://www.intely.io/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intely\naid: intely\nurl: https://www.intely.io/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control and bribery compliance\n  text: Customer represents, covenants, and warrants that Customer will comply with all applicable export control,\n    bribery, and other laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intely/eligibility/intely-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Intely's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Low-Code
- Automation
- API Platform
- Enterprise
---
