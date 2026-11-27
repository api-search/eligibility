---
api_specs:
- filename: capy-automations-api-openapi.yml
  format: yaml
  label: Capy Automations API
  slug: capy-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-automations-api-openapi.yml
- filename: capy-projects-api-openapi.yml
  format: yaml
  label: Capy Projects API
  slug: capy-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-projects-api-openapi.yml
- filename: capy-tasks-api-openapi.yml
  format: yaml
  label: Capy Tasks API
  slug: capy-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-tasks-api-openapi.yml
- filename: capy-threads-api-openapi.yml
  format: yaml
  label: Capy Threads API
  slug: capy-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-threads-api-openapi.yml
- filename: capy-usage-api-openapi.yml
  format: yaml
  label: Capy Usage API
  slug: capy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-usage-api-openapi.yml
- filename: capy-captains-api-openapi.yml
  format: yaml
  label: Capy Captains API
  slug: capy-captains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-captains-api-openapi.yml
- filename: capy-folders-api-openapi.yml
  format: yaml
  label: Capy Folders API
  slug: capy-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-folders-api-openapi.yml
- filename: capy-messages-api-openapi.yml
  format: yaml
  label: Capy Messages API
  slug: capy-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-messages-api-openapi.yml
- filename: capy-reviewfilters-api-openapi.yml
  format: yaml
  label: Capy Review Filters API
  slug: capy-reviewfilters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewfilters-api-openapi.yml
- filename: capy-reviewrules-api-openapi.yml
  format: yaml
  label: Capy Review Rules API
  slug: capy-reviewrules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewrules-api-openapi.yml
- filename: capy-reviews-api-openapi.yml
  format: yaml
  label: Capy Reviews API
  slug: capy-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviews-api-openapi.yml
- filename: capy-streams-api-openapi.yml
  format: yaml
  label: Capy Streams API
  slug: capy-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-streams-api-openapi.yml
- filename: capy-subagents-api-openapi.yml
  format: yaml
  label: Capy Subagents API
  slug: capy-subagents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-subagents-api-openapi.yml
- filename: capy-users-api-openapi.yml
  format: yaml
  label: Capy Users API
  slug: capy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country or region subject to comprehensive U.S. sanctions, and that you are not on any restricted-party list.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction if higher, to use the Services.
    type: individual
  - text: If you use the Services for an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction if higher, to use the Services.
    value: '18'
  restricted_uses:
  - summary: Professional use only
    text: The Services are intended for professional software development and business use, not for children.
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
name: Capy
provenance_date: '2026-11-09'
provider_name: Capy
provider_slug: capy
slug: capy-eligibility
source_date: '2026-11-09'
source_filename: capy-eligibility.yml
source_heading: Eligibility
source_page: https://capy.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capy\naid: capy\nurl: https://capy.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a country\n    or region subject to comprehensive U.S. sanctions, and that you are not on any restricted-party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction if higher, to use the Services.\n- type: business\n  text: If you use the Services for an organization, you represent that you have authority to\
  \ bind that organization.\nrestricted_uses:\n- summary: Professional use only\n  text: The Services are intended for professional software development and business use, not for children.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction if higher, to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/capy/eligibility/capy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Capy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Coding Agents
- Software Engineering
- Developer Tools
- Automation
- Code Review
- DevOps
---
