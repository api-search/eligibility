---
api_specs:
- filename: commareports-com-account-api-openapi.yml
  format: yaml
  label: Comma Account API
  slug: commareports-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-account-api-openapi.yml
- filename: commareports-com-assets-api-openapi.yml
  format: yaml
  label: Comma Assets API
  slug: commareports-com-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-assets-api-openapi.yml
- filename: commareports-com-comments-api-openapi.yml
  format: yaml
  label: Comma Comments API
  slug: commareports-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-comments-api-openapi.yml
- filename: commareports-com-connectors-api-openapi.yml
  format: yaml
  label: Comma Connectors API
  slug: commareports-com-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-connectors-api-openapi.yml
- filename: commareports-com-meta-api-openapi.yml
  format: yaml
  label: Comma Meta API
  slug: commareports-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-meta-api-openapi.yml
- filename: commareports-com-notifications-api-openapi.yml
  format: yaml
  label: Comma Notifications API
  slug: commareports-com-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-notifications-api-openapi.yml
- filename: commareports-com-reports-api-openapi.yml
  format: yaml
  label: Comma Reports API
  slug: commareports-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reports-api-openapi.yml
- filename: commareports-com-reviewers-api-openapi.yml
  format: yaml
  label: Comma Reviewers API
  slug: commareports-com-reviewers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reviewers-api-openapi.yml
- filename: commareports-com-reviews-api-openapi.yml
  format: yaml
  label: Comma Reviews API
  slug: commareports-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-reviews-api-openapi.yml
- filename: commareports-com-revisions-api-openapi.yml
  format: yaml
  label: Comma Revisions API
  slug: commareports-com-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-revisions-api-openapi.yml
- filename: commareports-com-routines-api-openapi.yml
  format: yaml
  label: Comma Routines API
  slug: commareports-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-routines-api-openapi.yml
- filename: commareports-com-sharing-api-openapi.yml
  format: yaml
  label: Comma Sharing API
  slug: commareports-com-sharing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-sharing-api-openapi.yml
- filename: commareports-com-skills-api-openapi.yml
  format: yaml
  label: Comma Skills API
  slug: commareports-com-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commareports-com/openapi/commareports-com-skills-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization, and “you” refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.
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
name: Comma
provenance_date: '2026-11-09'
provider_name: Comma
provider_slug: commareports-com
slug: commareports-com-eligibility
source_date: '2026-11-09'
source_filename: commareports-com-eligibility.yml
source_heading: Eligibility
source_page: https://commareports.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comma\naid: commareports-com\nurl: https://commareports.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization, and “you” refers to that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum age of digital consent in your country) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/commareports-com/eligibility/commareports-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Comma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Reports
- Collaboration
- Comments
- HTML
- MCP
- AI Agents
- Data Visualization
---
