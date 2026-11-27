---
api_specs:
- filename: aquabyte-behaviour-api-openapi.yml
  format: yaml
  label: Aquabyte Behaviour API
  slug: aquabyte-behaviour-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-behaviour-api-openapi.yml
- filename: aquabyte-biomass-api-openapi.yml
  format: yaml
  label: Aquabyte Biomass API
  slug: aquabyte-biomass-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-biomass-api-openapi.yml
- filename: aquabyte-environmental-api-openapi.yml
  format: yaml
  label: Aquabyte Environmental API
  slug: aquabyte-environmental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-environmental-api-openapi.yml
- filename: aquabyte-lice-api-openapi.yml
  format: yaml
  label: Aquabyte Lice API
  slug: aquabyte-lice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-lice-api-openapi.yml
- filename: aquabyte-sites-api-openapi.yml
  format: yaml
  label: Aquabyte Sites API
  slug: aquabyte-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-sites-api-openapi.yml
- filename: aquabyte-welfare-api-openapi.yml
  format: yaml
  label: Aquabyte Welfare API
  slug: aquabyte-welfare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-welfare-api-openapi.yml
- filename: aquabyte-pens-api-openapi.yml
  format: yaml
  label: Aquabyte Pens API
  slug: aquabyte-pens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquabyte/openapi/aquabyte-pens-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind such company or entity to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Aquaculture purposes only
    text: for purposes related to the Client's aquaculture activities
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
name: Aquabyte
provenance_date: '2026-11-09'
provider_name: Aquabyte
provider_slug: aquabyte
slug: aquabyte-eligibility
source_date: '2026-11-09'
source_filename: aquabyte-eligibility.yml
source_heading: Eligibility
source_page: https://www.aquabyte.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aquabyte\naid: aquabyte\nurl: https://www.aquabyte.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind such company or entity to this Agreement\nrestricted_uses:\n- summary: Aquaculture purposes only\n  text: for purposes related to the Client's aquaculture activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/aquabyte/eligibility/aquabyte-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Aquabyte's own page on 2026-11-09.
synthetic: false
tags:
- Aquaculture
- Fish Farming
- Computer Vision
- Machine Learning
- Biomass Estimation
- Sea Lice
- Fish Welfare
- Environmental Monitoring
- AgTech
- Norway
- Salmon
- Data
---
