---
api_specs:
- filename: companycam-checklists-api-openapi.yml
  format: yaml
  label: CompanyCam Checklists API
  slug: companycam-checklists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-checklists-api-openapi.yml
- filename: companycam-company-api-openapi.yml
  format: yaml
  label: CompanyCam Company API
  slug: companycam-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-company-api-openapi.yml
- filename: companycam-groups-api-openapi.yml
  format: yaml
  label: CompanyCam Groups API
  slug: companycam-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-groups-api-openapi.yml
- filename: companycam-photos-api-openapi.yml
  format: yaml
  label: CompanyCam Photos API
  slug: companycam-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-photos-api-openapi.yml
- filename: companycam-projects-api-openapi.yml
  format: yaml
  label: CompanyCam Projects API
  slug: companycam-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-projects-api-openapi.yml
- filename: companycam-tags-api-openapi.yml
  format: yaml
  label: CompanyCam Tags API
  slug: companycam-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-tags-api-openapi.yml
- filename: companycam-templates-api-openapi.yml
  format: yaml
  label: CompanyCam Templates API
  slug: companycam-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-templates-api-openapi.yml
- filename: companycam-users-api-openapi.yml
  format: yaml
  label: CompanyCam Users API
  slug: companycam-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-users-api-openapi.yml
- filename: companycam-videos-api-openapi.yml
  format: yaml
  label: CompanyCam Videos API
  slug: companycam-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-videos-api-openapi.yml
- filename: companycam-webhooks-api-openapi.yml
  format: yaml
  label: CompanyCam Webhooks API
  slug: companycam-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companycam/openapi/companycam-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the business entity associated with the billing account for the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitor access
    text: CompanyCam’s direct competitors may not access the Services.
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
name: CompanyCam
provenance_date: '2026-11-09'
provider_name: CompanyCam
provider_slug: companycam
slug: companycam-eligibility
source_date: '2026-11-09'
source_filename: companycam-eligibility.yml
source_heading: Eligibility
source_page: https://companycam.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CompanyCam\naid: companycam\nurl: https://companycam.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the business entity associated with the billing account for the Services\nrestricted_uses:\n- summary: Competitor access\n  text: CompanyCam’s direct competitors may not access the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/companycam/eligibility/companycam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CompanyCam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Photos
- Field Service Management
- Project Management
- Contractors
- Documentation
- Webhook
---
