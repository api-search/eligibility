---
api_specs:
- filename: flexpa-access-tokens-api-openapi.yml
  format: yaml
  label: Flexpa Access Tokens API
  slug: flexpa-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-access-tokens-api-openapi.yml
- filename: flexpa-claims-data-api-openapi.yml
  format: yaml
  label: Flexpa Claims Data API
  slug: flexpa-claims-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-claims-data-api-openapi.yml
- filename: flexpa-fhir-api-openapi.yml
  format: yaml
  label: Flexpa FHIR API
  slug: flexpa-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-fhir-api-openapi.yml
- filename: flexpa-link-api-openapi.yml
  format: yaml
  label: Flexpa Link API
  slug: flexpa-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-link-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to the Flexpa Platform and Services is for End Users only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Flexpa Platform for lawful purposes only.
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
name: Flexpa
provenance_date: '2026-11-09'
provider_name: Flexpa
provider_slug: flexpa
slug: flexpa-eligibility
source_date: '2026-11-09'
source_filename: flexpa-eligibility.yml
source_heading: Eligibility
source_page: https://www.flexpa.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flexpa\naid: flexpa\nurl: https://www.flexpa.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to the Flexpa Platform and Services is for End Users only.\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Flexpa Platform for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flexpa/eligibility/flexpa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Flexpa's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Patient Access
- Claims Data
- Health Insurance
---
