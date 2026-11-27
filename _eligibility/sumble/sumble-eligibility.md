---
api_specs:
- filename: sumble-contact-lists-api-openapi.yml
  format: yaml
  label: Sumble Contact Lists API
  slug: sumble-contact-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-contact-lists-api-openapi.yml
- filename: sumble-jobs-api-openapi.yml
  format: yaml
  label: Sumble Jobs API
  slug: sumble-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-jobs-api-openapi.yml
- filename: sumble-organization-lists-api-openapi.yml
  format: yaml
  label: Sumble Organization Lists API
  slug: sumble-organization-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-organization-lists-api-openapi.yml
- filename: sumble-organizations-api-openapi.yml
  format: yaml
  label: Sumble Organizations API
  slug: sumble-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-organizations-api-openapi.yml
- filename: sumble-people-api-openapi.yml
  format: yaml
  label: Sumble People API
  slug: sumble-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-people-api-openapi.yml
- filename: sumble-projects-api-openapi.yml
  format: yaml
  label: Sumble Projects API
  slug: sumble-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-projects-api-openapi.yml
- filename: sumble-signals-api-openapi.yml
  format: yaml
  label: Sumble Signals API
  slug: sumble-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-signals-api-openapi.yml
- filename: sumble-support-api-openapi.yml
  format: yaml
  label: Sumble Support API
  slug: sumble-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-support-api-openapi.yml
- filename: sumble-teams-api-openapi.yml
  format: yaml
  label: Sumble Teams API
  slug: sumble-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-teams-api-openapi.yml
- filename: sumble-technologies-api-openapi.yml
  format: yaml
  label: Sumble Technologies API
  slug: sumble-technologies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sumble/openapi/sumble-technologies-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then "you" includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: you represent and warrant that (a) you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: the Services may not be exported or re-exported (a) into any U.S. embargoed countries or any country that has been designated by the U.S. Government as a "terrorist supporting" country
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
name: Sumble
provenance_date: '2026-11-10'
provider_name: Sumble
provider_slug: sumble
slug: sumble-eligibility
source_date: '2026-11-10'
source_filename: sumble-eligibility.yml
source_heading: Eligibility
source_page: https://sumble.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sumble\naid: sumble\nurl: https://sumble.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then \"you\" includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Export restrictions\n  text: the Services may not be exported or re-exported (a) into any U.S. embargoed countries or any country that\n    has been designated by the U.S. Government as a \"terrorist\
  \ supporting\" country\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that (a) you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/sumble/eligibility/sumble-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sumble's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Account Intelligence
- Sales Intelligence
- Data Enrichment
- Go-To-Market
- Technographics
- People Data
- Job Posts
- Signals
- MCP
---
