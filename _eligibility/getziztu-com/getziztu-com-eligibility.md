---
api_specs:
- filename: getziztu-com-characters-api-openapi.yml
  format: yaml
  label: getziztu-com Characters API
  slug: getziztu-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-characters-api-openapi.yml
- filename: getziztu-com-credits-api-openapi.yml
  format: yaml
  label: getziztu-com Credits API
  slug: getziztu-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-credits-api-openapi.yml
- filename: getziztu-com-director-api-openapi.yml
  format: yaml
  label: getziztu-com Director API
  slug: getziztu-com-director-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-director-api-openapi.yml
- filename: getziztu-com-export-api-openapi.yml
  format: yaml
  label: getziztu-com Export API
  slug: getziztu-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-export-api-openapi.yml
- filename: getziztu-com-generate-api-openapi.yml
  format: yaml
  label: getziztu-com Generate API
  slug: getziztu-com-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-generate-api-openapi.yml
- filename: getziztu-com-jobs-api-openapi.yml
  format: yaml
  label: getziztu-com Jobs API
  slug: getziztu-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-jobs-api-openapi.yml
- filename: getziztu-com-media-api-openapi.yml
  format: yaml
  label: getziztu-com Media API
  slug: getziztu-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-media-api-openapi.yml
- filename: getziztu-com-meta-api-openapi.yml
  format: yaml
  label: getziztu-com Meta API
  slug: getziztu-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-meta-api-openapi.yml
- filename: getziztu-com-music-api-openapi.yml
  format: yaml
  label: getziztu-com Music API
  slug: getziztu-com-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-music-api-openapi.yml
- filename: getziztu-com-places-api-openapi.yml
  format: yaml
  label: getziztu-com Places API
  slug: getziztu-com-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-places-api-openapi.yml
- filename: getziztu-com-projects-api-openapi.yml
  format: yaml
  label: getziztu-com Projects API
  slug: getziztu-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-projects-api-openapi.yml
- filename: getziztu-com-script-api-openapi.yml
  format: yaml
  label: getziztu-com Script API
  slug: getziztu-com-script-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-script-api-openapi.yml
- filename: getziztu-com-shots-api-openapi.yml
  format: yaml
  label: getziztu-com Shots API
  slug: getziztu-com-shots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-shots-api-openapi.yml
- filename: getziztu-com-tools-api-openapi.yml
  format: yaml
  label: getziztu-com Tools API
  slug: getziztu-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getziztu-com/openapi/getziztu-com-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Ziztu for a company, you confirm you may accept these terms for it.
    type: business
  - text: You must be at least 18, or at least 13 with the permission of a parent or guardian.
    type: individual
  minimum_age:
    text: You must be at least 18, or at least 13 with the permission of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Sexual images of real people
    text: Create sexual or nude images of real people, or any content that shows a real person doing or saying something they did not do or say without their consent.
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
name: getziztu-com
provenance_date: '2026-11-09'
provider_name: getziztu-com
provider_slug: getziztu-com
slug: getziztu-com-eligibility
source_date: '2026-11-09'
source_filename: getziztu-com-eligibility.yml
source_heading: Eligibility
source_page: https://getziztu.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: getziztu-com\naid: getziztu-com\nurl: https://getziztu.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Ziztu for a company, you confirm you may accept these terms for it.\n- type: individual\n  text: You must be at least 18, or at least 13 with the permission of a parent or guardian.\nrestricted_uses:\n- summary: Sexual images of real people\n  text: Create sexual or nude images of real people, or any content that shows a real person doing or saying something\n    they did not do or say without their consent.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or at least 13 with the permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/getziztu-com/eligibility/getziztu-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from getziztu-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Social Media
- Content Creation
---
