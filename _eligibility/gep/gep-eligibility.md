---
api_specs:
- filename: gep-leo-gr-domaingateway-api-api-openapi.yml
  format: yaml
  label: GEP Leo Gr Domaingateway API
  slug: gep-leo-gr-domaingateway-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gep/openapi/gep-leo-gr-domaingateway-api-api-openapi.yml
- filename: gep-leo-order-aggregator-api-api-openapi.yml
  format: yaml
  label: GEP Leo Order Aggregator API
  slug: gep-leo-order-aggregator-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gep/openapi/gep-leo-order-aggregator-api-api-openapi.yml
- filename: gep-leo-sc-aggregator-api-api-openapi.yml
  format: yaml
  label: GEP Leo Sc Aggregator API
  slug: gep-leo-sc-aggregator-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gep/openapi/gep-leo-sc-aggregator-api-api-openapi.yml
- filename: gep-token-api-openapi.yml
  format: yaml
  label: GEP Token API
  slug: gep-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gep/openapi/gep-token-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Website, including any material or content therein, is not intended for individuals that are under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Website, including any material or content therein, are provided for Your informational, personal and non-commercial use only.
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
name: GEP
provenance_date: '2026-11-09'
provider_name: GEP
provider_slug: gep
slug: gep-eligibility
source_date: '2026-11-09'
source_filename: gep-eligibility.yml
source_heading: Eligibility
source_page: https://www.gep.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GEP\naid: gep\nurl: https://www.gep.com/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The Website, including any material or content therein, are provided for Your informational, personal and\n    non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website, including any material or content therein, is not intended for individuals that are under the\n    age of 18.\n"
source_yaml_url: https://artifacts.apis.io/gep/eligibility/gep-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from GEP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Procurement
- Supply Chain
- Artificial Intelligence
- Software-as-a-Service
---
