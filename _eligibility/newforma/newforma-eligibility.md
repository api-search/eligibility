---
api_specs:
- filename: newforma-hub-api-openapi.yml
  format: yaml
  label: Newforma Hub API
  slug: newforma-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newforma/openapi/newforma-hub-api-openapi.yml
- filename: newforma-issue-api-openapi.yml
  format: yaml
  label: Newforma Issue API
  slug: newforma-issue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newforma/openapi/newforma-issue-api-openapi.yml
- filename: newforma-project-api-openapi.yml
  format: yaml
  label: Newforma Project API
  slug: newforma-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newforma/openapi/newforma-project-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept this Agreement for an entity, you represent that you have the authority to bind the entity to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Developer must (a) submit such Application to Newforma for approval
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Newforma
provenance_date: '2026-11-10'
provider_name: Newforma
provider_slug: newforma
slug: newforma-eligibility
source_date: '2026-11-10'
source_filename: newforma-eligibility.yml
source_heading: Eligibility
source_page: https://www.newforma.com/newforma-api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Newforma\naid: newforma\nurl: https://www.newforma.com/newforma-api/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept this Agreement for an entity, you represent that you have the authority to bind the entity\n    to this Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Developer must (a) submit such Application to Newforma for approval\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/newforma/eligibility/newforma-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Newforma's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AEC
- Construction
- Architecture
- Engineering
- BIM
- Building Information Modeling
- Project Management
- Issue Tracking
- Collaboration
---
