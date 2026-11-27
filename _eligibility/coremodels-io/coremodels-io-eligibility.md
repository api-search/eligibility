---
api_specs:
- filename: coremodels-io-integrationapi-api-openapi.yml
  format: yaml
  label: coremodels-io Integration API
  slug: coremodels-io-integrationapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coremodels-io/openapi/coremodels-io-integrationapi-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Builder accounts are for one named person.
    type: individual
  - text: If you are accepting on behalf of an organization, you confirm you have authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
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
name: coremodels-io
provenance_date: '2026-11-09'
provider_name: coremodels-io
provider_slug: coremodels-io
slug: coremodels-io-eligibility
source_date: '2026-11-09'
source_filename: coremodels-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.coremodels.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: coremodels-io\naid: coremodels-io\nurl: https://www.coremodels.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Builder accounts are for one named person.\n- type: business\n  text: If you are accepting on behalf of an organization, you confirm you have authority to do so.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coremodels-io/eligibility/coremodels-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from coremodels-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Modeling
- API Platform
- Integration
- Schema-Mapping
---
