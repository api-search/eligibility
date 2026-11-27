---
api_specs:
- filename: octoparse-action-api-openapi.yml
  format: yaml
  label: Octoparse Action API
  slug: octoparse-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-action-api-openapi.yml
- filename: octoparse-actions-api-openapi.yml
  format: yaml
  label: Octoparse Actions API
  slug: octoparse-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-actions-api-openapi.yml
- filename: octoparse-cloud-extraction-api-openapi.yml
  format: yaml
  label: Octoparse Cloud_ Extraction API
  slug: octoparse-cloud-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-cloud-extraction-api-openapi.yml
- filename: octoparse-copy-api-openapi.yml
  format: yaml
  label: Octoparse Copy API
  slug: octoparse-copy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-copy-api-openapi.yml
- filename: octoparse-data-api-openapi.yml
  format: yaml
  label: Octoparse Data API
  slug: octoparse-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-data-api-openapi.yml
- filename: octoparse-files-api-openapi.yml
  format: yaml
  label: Octoparse Files API
  slug: octoparse-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-files-api-openapi.yml
- filename: octoparse-group-api-openapi.yml
  format: yaml
  label: Octoparse Group API
  slug: octoparse-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-group-api-openapi.yml
- filename: octoparse-groups-api-openapi.yml
  format: yaml
  label: Octoparse Groups API
  slug: octoparse-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-groups-api-openapi.yml
- filename: octoparse-items-api-openapi.yml
  format: yaml
  label: Octoparse Items API
  slug: octoparse-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-items-api-openapi.yml
- filename: octoparse-search-api-openapi.yml
  format: yaml
  label: Octoparse Search API
  slug: octoparse-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-search-api-openapi.yml
- filename: octoparse-statuses-api-openapi.yml
  format: yaml
  label: Octoparse Statuses API
  slug: octoparse-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-statuses-api-openapi.yml
- filename: octoparse-stop-api-openapi.yml
  format: yaml
  label: Octoparse Stop API
  slug: octoparse-stop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-stop-api-openapi.yml
- filename: octoparse-subtasks-api-openapi.yml
  format: yaml
  label: Octoparse Subtasks API
  slug: octoparse-subtasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-subtasks-api-openapi.yml
- filename: octoparse-token-api-openapi.yml
  format: yaml
  label: Octoparse Token API
  slug: octoparse-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octoparse/openapi/octoparse-token-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the U.S.
  entity_types:
  - text: an individual subscriber, customer, member, or user of at least 18 years of age
    type: individual
  - text: a single company, organization, or entity
    type: business
  minimum_age:
    text: THE SERVICE IS NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Direct competitors
    text: Access the Service if you are a direct competitor of Octoparse
  - summary: Embargoed countries
    text: You may not use the Service if you are a resident of a country embargoed by the United States
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
name: Octoparse
provenance_date: '2026-11-10'
provider_name: Octoparse
provider_slug: octoparse
slug: octoparse-eligibility
source_date: '2026-11-10'
source_filename: octoparse-eligibility.yml
source_heading: Eligibility
source_page: https://www.octoparse.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Octoparse\naid: octoparse\nurl: https://www.octoparse.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the U.S.\nentity_types:\n- type: individual\n  text: an individual subscriber, customer, member, or user of at least 18 years of age\n- type: business\n  text: a single company, organization, or entity\nrestricted_uses:\n- summary: Direct competitors\n  text: Access the Service if you are a direct competitor\
  \ of Octoparse\n- summary: Embargoed countries\n  text: You may not use the Service if you are a resident of a country embargoed by the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE SERVICE IS NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/octoparse/eligibility/octoparse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Octoparse's own page on 2026-11-10.
synthetic: false
tags:
- Harvesting
- Web Scraping
---
