---
api_specs:
- filename: emitrr-actions-api-openapi.yml
  format: yaml
  label: Emitrr Actions API
  slug: emitrr-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-actions-api-openapi.yml
- filename: emitrr-branches-api-openapi.yml
  format: yaml
  label: Emitrr Branches API
  slug: emitrr-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-branches-api-openapi.yml
- filename: emitrr-core-api-openapi.yml
  format: yaml
  label: Emitrr Core API
  slug: emitrr-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-core-api-openapi.yml
- filename: emitrr-filters-api-openapi.yml
  format: yaml
  label: Emitrr Filters API
  slug: emitrr-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-filters-api-openapi.yml
- filename: emitrr-health-api-openapi.yml
  format: yaml
  label: Emitrr Health API
  slug: emitrr-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-health-api-openapi.yml
- filename: emitrr-triggers-api-openapi.yml
  format: yaml
  label: Emitrr Triggers API
  slug: emitrr-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-triggers-api-openapi.yml
- filename: emitrr-workflows-api-openapi.yml
  format: yaml
  label: Emitrr Workflows API
  slug: emitrr-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emitrr/openapi/emitrr-workflows-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not access or use the Services if Customer is located in any jurisdiction in which the provision of the Services, Software or other components is prohibited under U.S. or other applicable laws or regulations
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: use of the Services for any purpose prohibited by applicable export laws and regulations, including without limitation, nuclear, chemical, or biological weapons proliferation, or development of missile technology
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
name: Emitrr
provenance_date: '2026-11-09'
provider_name: Emitrr
provider_slug: emitrr
slug: emitrr-eligibility
source_date: '2026-11-09'
source_filename: emitrr-eligibility.yml
source_heading: Eligibility
source_page: https://emitrr.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Emitrr\naid: emitrr\nurl: https://emitrr.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not access or use the Services if Customer is located in any jurisdiction in which the provision\n    of the Services, Software or other components is prohibited under U.S. or other applicable laws or regulations\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: use of the Services for any purpose prohibited by applicable export laws and regulations, including without\n    limitation, nuclear, chemical, or biological weapons proliferation,\
  \ or development of missile technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emitrr/eligibility/emitrr-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Emitrr's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Artificial Intelligence
- Communications
- Messaging
- Software-as-a-Service
---
