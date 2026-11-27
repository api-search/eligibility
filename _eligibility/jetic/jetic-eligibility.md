---
api_specs:
- filename: jetic-api-specifications-api-openapi.yml
  format: yaml
  label: Jetic API Specifications API
  slug: jetic-api-specifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetic/openapi/jetic-api-specifications-api-openapi.yml
- filename: jetic-clusters-api-openapi.yml
  format: yaml
  label: Jetic Clusters API
  slug: jetic-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetic/openapi/jetic-clusters-api-openapi.yml
- filename: jetic-deployments-api-openapi.yml
  format: yaml
  label: Jetic Deployments API
  slug: jetic-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetic/openapi/jetic-deployments-api-openapi.yml
- filename: jetic-integrations-api-openapi.yml
  format: yaml
  label: Jetic Integrations API
  slug: jetic-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetic/openapi/jetic-integrations-api-openapi.yml
- filename: jetic-monitoring-api-openapi.yml
  format: yaml
  label: Jetic Monitoring API
  slug: jetic-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jetic/openapi/jetic-monitoring-api-openapi.yml
claim_count: 2
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
  - summary: Violating applicable laws
    text: use this website or its associated services in violation of any applicable laws or regulations
  - summary: Transmitting unlawful material
    text: use this website or its associated services to transmit or publish any harassing, indecent, obscene, fraudulent, or unlawful material
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
name: Jetic
provenance_date: '2026-11-09'
provider_name: Jetic
provider_slug: jetic
slug: jetic-eligibility
source_date: '2026-11-09'
source_filename: jetic-eligibility.yml
source_heading: Eligibility
source_page: https://jetic.io/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jetic\naid: jetic\nurl: https://jetic.io/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violating applicable laws\n  text: use this website or its associated services in violation of any applicable laws or regulations\n- summary: Transmitting unlawful material\n  text: use this website or its associated services to transmit or publish any harassing, indecent, obscene, fraudulent,\n    or unlawful material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/jetic/eligibility/jetic-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Jetic's own page on 2026-11-09.
synthetic: false
tags:
- Apache Camel
- Integration
- iPaaS
- Pro-Code-API-Composition
---
