---
api_specs:
- filename: striim-application-api-openapi.yml
  format: yaml
  label: Striim Application API
  slug: striim-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-application-api-openapi.yml
- filename: striim-applicationmetadata-api-openapi.yml
  format: yaml
  label: Striim Application Metadata API
  slug: striim-applicationmetadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-applicationmetadata-api-openapi.yml
- filename: striim-checkpoint-api-openapi.yml
  format: yaml
  label: Striim Checkpoint API
  slug: striim-checkpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-checkpoint-api-openapi.yml
- filename: striim-monitoring-api-openapi.yml
  format: yaml
  label: Striim Monitoring API
  slug: striim-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-monitoring-api-openapi.yml
- filename: striim-template-api-openapi.yml
  format: yaml
  label: Striim Template API
  slug: striim-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-template-api-openapi.yml
- filename: striim-tqlfiles-api-openapi.yml
  format: yaml
  label: Striim Tqlfiles API
  slug: striim-tqlfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-tqlfiles-api-openapi.yml
- filename: striim-tungsten-api-openapi.yml
  format: yaml
  label: Striim Tungsten API
  slug: striim-tungsten-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/striim/openapi/striim-tungsten-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Customer represents and warrants that it is not ... located, organized, or resident in a country or region that is subject to comprehensive U.S. trade sanctions (currently, Cuba, Iran, North Korea, Syria,
  entity_types:
  - text: “Customer” means that person or entity listed on the Order Form.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Trial version limited to evaluation
    text: The Trial Version may be Used only to review and evaluate the Software.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Striim
provenance_date: '2026-11-10'
provider_name: Striim
provider_slug: striim
slug: striim-eligibility
source_date: '2026-11-10'
source_filename: striim-eligibility.yml
source_heading: Eligibility
source_page: https://www.striim.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Striim\naid: striim\nurl: https://www.striim.com/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customer represents and warrants that it is not ... located, organized, or resident in a country or region\n    that is subject to comprehensive U.S. trade sanctions (currently, Cuba, Iran, North Korea, Syria,\nentity_types:\n- type: other\n  text: “Customer” means that person or entity listed on the Order Form.\nrestricted_uses:\n- summary: Trial version limited to evaluation\n  text: The Trial Version may be Used only to review and evaluate the Software.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/striim/eligibility/striim-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Striim's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Streaming
- Change Data Capture
- Real-Time
- Data Integration
- Streaming Analytics
---
