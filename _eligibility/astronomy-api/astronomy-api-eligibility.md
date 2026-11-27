---
api_specs:
- filename: astronomy-api-bodies-api-openapi.yml
  format: yaml
  label: Astronomy API Bodies API
  slug: astronomy-api-bodies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astronomy-api/openapi/astronomy-api-bodies-api-openapi.yml
- filename: astronomy-api-events-api-openapi.yml
  format: yaml
  label: Astronomy API Events API
  slug: astronomy-api-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astronomy-api/openapi/astronomy-api-events-api-openapi.yml
- filename: astronomy-api-search-api-openapi.yml
  format: yaml
  label: Astronomy API Search API
  slug: astronomy-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astronomy-api/openapi/astronomy-api-search-api-openapi.yml
- filename: astronomy-api-studio-api-openapi.yml
  format: yaml
  label: Astronomy API Studio API
  slug: astronomy-api-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astronomy-api/openapi/astronomy-api-studio-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are a person barred from receiving the Service under the laws of the United States or any other countries, including the country in which you are resident or from which you access and use the Service.
  entity_types:
  - text: If you are an individual, you represent and warrant that you have the legal right to enter into the Terms.
    type: individual
  - text: If you are entering into the Terms on behalf of a legal entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: You affirm that you are over the age of 13, as the Service is not intended for children under 13.
    value: '13'
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
name: Astronomy API
provenance_date: '2026-11-09'
provider_name: Astronomy API
provider_slug: astronomy-api
slug: astronomy-api-eligibility
source_date: '2026-11-09'
source_filename: astronomy-api-eligibility.yml
source_heading: Eligibility
source_page: https://astronomyapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astronomy API\naid: astronomy-api\nurl: https://astronomyapi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are a person barred from receiving the Service under the laws of the\n    United States or any other countries, including the country in which you are resident or from which you access\n    and use the Service.\nentity_types:\n- type: individual\n  text: If you are an individual, you represent and warrant that you have the legal right to enter into the Terms.\n- type: business\n  text: If you are entering into the Terms\
  \ on behalf of a legal entity, you represent and warrant that you have\n    the authority to bind that entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You affirm that you are over the age of 13, as the Service is not intended for children under 13.\n"
source_yaml_url: https://artifacts.apis.io/astronomy-api/eligibility/astronomy-api-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Astronomy API's own page on 2026-11-09.
synthetic: false
tags:
- Astronomy
- Celestial Data
- Space
- Moon Phases
- Star Charts
---
