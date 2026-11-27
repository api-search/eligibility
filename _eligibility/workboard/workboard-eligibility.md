---
api_specs:
- filename: workboard-activity-action-items-api-openapi.yml
  format: yaml
  label: WorkBoard Activity (Action Items) API
  slug: workboard-activity-action-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-activity-action-items-api-openapi.yml
- filename: workboard-custom-attributes-api-openapi.yml
  format: yaml
  label: WorkBoard Custom Attributes API
  slug: workboard-custom-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-custom-attributes-api-openapi.yml
- filename: workboard-goal-objective-api-openapi.yml
  format: yaml
  label: WorkBoard Goal (Objective) API
  slug: workboard-goal-objective-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-goal-objective-api-openapi.yml
- filename: workboard-metric-key-result-api-openapi.yml
  format: yaml
  label: WorkBoard Metric (Key Result) API
  slug: workboard-metric-key-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-metric-key-result-api-openapi.yml
- filename: workboard-tags-api-openapi.yml
  format: yaml
  label: WorkBoard Tags API
  slug: workboard-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-tags-api-openapi.yml
- filename: workboard-team-api-openapi.yml
  format: yaml
  label: WorkBoard Team API
  slug: workboard-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-team-api-openapi.yml
- filename: workboard-user-api-openapi.yml
  format: yaml
  label: WorkBoard User API
  slug: workboard-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-user-api-openapi.yml
- filename: workboard-user-goals-user-objectives-api-openapi.yml
  format: yaml
  label: WorkBoard User Goals (User Objectives) API
  slug: workboard-user-goals-user-objectives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-user-goals-user-objectives-api-openapi.yml
- filename: workboard-webhook-api-openapi.yml
  format: yaml
  label: WorkBoard Webhook API
  slug: workboard-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-webhook-api-openapi.yml
- filename: workboard-workstream-api-openapi.yml
  format: yaml
  label: WorkBoard Workstream API
  slug: workboard-workstream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-workstream-api-openapi.yml
- filename: workboard-data-stream-api-openapi.yml
  format: yaml
  label: WorkBoard Data Stream API
  slug: workboard-data-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workboard/openapi/workboard-data-stream-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Local Laws; Export Control: User Sites and/or Third Party Content may not be appropriate or available for use outside of the United States of America.'
  entity_types:
  - text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'
    type: individual
  minimum_age:
    text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'
    value: '18'
  restricted_uses:
  - summary: Unauthorized use of Content or Services
    text: Unauthorized use of any User Content, the Services or Third Party Content contained on this Site may violate certain laws and regulations.
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
name: WorkBoard
provenance_date: '2026-11-10'
provider_name: WorkBoard
provider_slug: workboard
slug: workboard-eligibility
source_date: '2026-11-10'
source_filename: workboard-eligibility.yml
source_heading: Eligibility
source_page: https://www.workboard.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WorkBoard\naid: workboard\nurl: https://www.workboard.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Local Laws; Export Control: User Sites and/or Third Party Content may not be appropriate or available for\n    use outside of the United States of America.'\nentity_types:\n- type: individual\n  text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years\n    of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'\nrestricted_uses:\n- summary: Unauthorized use of\
  \ Content or Services\n  text: Unauthorized use of any User Content, the Services or Third Party Content contained on this Site may violate\n    certain laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'Registration and participation on the Site and the Services is restricted to: individuals over 18 years\n    of age; emancipated minors; and users under age 18 who possess legal parental or guardian consent.'\n"
source_yaml_url: https://artifacts.apis.io/workboard/eligibility/workboard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WorkBoard's own page on 2026-11-10.
synthetic: false
tags:
- OKRs
- Strategy Execution
- Goals
- Key Results
- Enterprise
- AI Agents
- Performance Management
- Strategic Portfolio Management
---
