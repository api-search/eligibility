---
api_specs:
- filename: 3gppscout-com-analysis-api-openapi.yml
  format: yaml
  label: 3GPP Scout Analysis API
  slug: 3gppscout-com-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-analysis-api-openapi.yml
- filename: 3gppscout-com-documents-api-openapi.yml
  format: yaml
  label: 3GPP Scout Documents API
  slug: 3gppscout-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-documents-api-openapi.yml
- filename: 3gppscout-com-follow-api-openapi.yml
  format: yaml
  label: 3GPP Scout Follow API
  slug: 3gppscout-com-follow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-follow-api-openapi.yml
- filename: 3gppscout-com-images-api-openapi.yml
  format: yaml
  label: 3GPP Scout Images API
  slug: 3gppscout-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-images-api-openapi.yml
- filename: 3gppscout-com-meetings-api-openapi.yml
  format: yaml
  label: 3GPP Scout Meetings API
  slug: 3gppscout-com-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-meetings-api-openapi.yml
- filename: 3gppscout-com-news-api-openapi.yml
  format: yaml
  label: 3GPP Scout News API
  slug: 3gppscout-com-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-news-api-openapi.yml
- filename: 3gppscout-com-organizations-api-openapi.yml
  format: yaml
  label: 3GPP Scout Organizations API
  slug: 3gppscout-com-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-organizations-api-openapi.yml
- filename: 3gppscout-com-positions-api-openapi.yml
  format: yaml
  label: 3GPP Scout Positions API
  slug: 3gppscout-com-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-positions-api-openapi.yml
- filename: 3gppscout-com-rfcs-api-openapi.yml
  format: yaml
  label: 3GPP Scout Rfcs API
  slug: 3gppscout-com-rfcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-rfcs-api-openapi.yml
- filename: 3gppscout-com-search-api-openapi.yml
  format: yaml
  label: 3GPP Scout Search API
  slug: 3gppscout-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-search-api-openapi.yml
- filename: 3gppscout-com-sections-api-openapi.yml
  format: yaml
  label: 3GPP Scout Sections API
  slug: 3gppscout-com-sections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-sections-api-openapi.yml
- filename: 3gppscout-com-system-api-openapi.yml
  format: yaml
  label: 3GPP Scout System API
  slug: 3gppscout-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-system-api-openapi.yml
- filename: 3gppscout-com-tdocs-api-openapi.yml
  format: yaml
  label: 3GPP Scout Tdocs API
  slug: 3gppscout-com-tdocs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3gppscout-com/openapi/3gppscout-com-tdocs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal or internal business purposes
    type: business
  minimum_age:
    text: You must be at least 16 years old to use our Services.
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: Use the Services for any illegal or unauthorized purpose.
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
name: 3GPP Scout
provenance_date: '2026-11-09'
provider_name: 3GPP Scout
provider_slug: 3gppscout-com
slug: 3gppscout-com-eligibility
source_date: '2026-11-09'
source_filename: 3gppscout-com-eligibility.yml
source_heading: Eligibility
source_page: https://3gppscout.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3GPP Scout\naid: 3gppscout-com\nurl: https://3gppscout.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for your personal or internal business purposes\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: Use the Services for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/3gppscout-com/eligibility/3gppscout-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 3GPP Scout's own page on 2026-11-09.
synthetic: false
tags:
- 3GPP
- Standards
- Search
- Artificial Intelligence
---
