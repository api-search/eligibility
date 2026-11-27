---
api_specs:
- filename: coordinate-comments-api-openapi.yml
  format: yaml
  label: Coordinate Comments API
  slug: coordinate-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-comments-api-openapi.yml
- filename: coordinate-entity-api-openapi.yml
  format: yaml
  label: Coordinate Entity API
  slug: coordinate-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-entity-api-openapi.yml
- filename: coordinate-goals-api-openapi.yml
  format: yaml
  label: Coordinate Goals API
  slug: coordinate-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-goals-api-openapi.yml
- filename: coordinate-groups-api-openapi.yml
  format: yaml
  label: Coordinate Groups API
  slug: coordinate-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-groups-api-openapi.yml
- filename: coordinate-organizations-api-openapi.yml
  format: yaml
  label: Coordinate Organizations API
  slug: coordinate-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-organizations-api-openapi.yml
- filename: coordinate-progress-reports-api-openapi.yml
  format: yaml
  label: Coordinate Progress Reports API
  slug: coordinate-progress-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-progress-reports-api-openapi.yml
- filename: coordinate-project-pages-api-openapi.yml
  format: yaml
  label: Coordinate Project Pages API
  slug: coordinate-project-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-project-pages-api-openapi.yml
- filename: coordinate-projects-api-openapi.yml
  format: yaml
  label: Coordinate Projects API
  slug: coordinate-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-projects-api-openapi.yml
- filename: coordinate-stakeholders-api-openapi.yml
  format: yaml
  label: Coordinate Stakeholders API
  slug: coordinate-stakeholders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-stakeholders-api-openapi.yml
- filename: coordinate-storage-api-openapi.yml
  format: yaml
  label: Coordinate Storage API
  slug: coordinate-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-storage-api-openapi.yml
- filename: coordinate-tasks-api-openapi.yml
  format: yaml
  label: Coordinate Tasks API
  slug: coordinate-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-tasks-api-openapi.yml
- filename: coordinate-users-api-openapi.yml
  format: yaml
  label: Coordinate Users API
  slug: coordinate-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-users-api-openapi.yml
- filename: coordinate-webhooks-api-openapi.yml
  format: yaml
  label: Coordinate Webhooks API
  slug: coordinate-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-webhooks-api-openapi.yml
- filename: coordinate-coordinate-rest-api-api-openapi.yml
  format: yaml
  label: Coordinate REST API
  slug: coordinate-coordinate-rest-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordinate/openapi/coordinate-coordinate-rest-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not and will not when using the Site be located in, under the control of, or a national or resident of a U.S. embargoed country or territory
  entity_types:
  - text: (a) of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction) and competent to agree to these Terms
    type: individual
  minimum_age:
    text: (18 years of age or older or otherwise of legal age in your resident jurisdiction)
    value: '18'
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
name: Coordinate
provenance_date: '2026-11-09'
provider_name: Coordinate
provider_slug: coordinate
slug: coordinate-eligibility
source_date: '2026-11-09'
source_filename: coordinate-eligibility.yml
source_heading: Eligibility
source_page: https://www.coordinatehq.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coordinate\naid: coordinate\nurl: https://www.coordinatehq.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not and will not when using the Site be located in, under the control\n    of, or a national or resident of a U.S. embargoed country or territory\nentity_types:\n- type: individual\n  text: (a) of legal age (18 years of age or older or otherwise of legal age in your resident jurisdiction) and\n    competent to agree to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (18 years of age or older or otherwise of legal age in your resident jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/coordinate/eligibility/coordinate-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Coordinate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Saas
- Project Management
- Client Portal
- Client Onboarding
- Professional Services
- Workflow Automation
- Collaboration
- Webhook
---
