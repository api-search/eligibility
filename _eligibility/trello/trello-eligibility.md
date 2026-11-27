---
api_specs:
- filename: trello-webhooks-asyncapi.yml
  format: yaml
  label: Trello Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/trello/asyncapi/trello-webhooks-asyncapi.yml
- filename: trello-actions-api-openapi.yml
  format: yaml
  label: trello Actions API
  slug: trello-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-actions-api-openapi.yml
- filename: trello-boards-api-openapi.yml
  format: yaml
  label: trello Boards API
  slug: trello-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-boards-api-openapi.yml
- filename: trello-cards-api-openapi.yml
  format: yaml
  label: trello Cards API
  slug: trello-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-cards-api-openapi.yml
- filename: trello-checklists-api-openapi.yml
  format: yaml
  label: trello Checklists API
  slug: trello-checklists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-checklists-api-openapi.yml
- filename: trello-labels-api-openapi.yml
  format: yaml
  label: trello Labels API
  slug: trello-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-labels-api-openapi.yml
- filename: trello-lists-api-openapi.yml
  format: yaml
  label: trello Lists API
  slug: trello-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-lists-api-openapi.yml
- filename: trello-members-api-openapi.yml
  format: yaml
  label: trello Members API
  slug: trello-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-members-api-openapi.yml
- filename: trello-notifications-api-openapi.yml
  format: yaml
  label: trello Notifications API
  slug: trello-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-notifications-api-openapi.yml
- filename: trello-organizations-api-openapi.yml
  format: yaml
  label: trello Organizations API
  slug: trello-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-organizations-api-openapi.yml
- filename: trello-plugins-api-openapi.yml
  format: yaml
  label: trello Plugins API
  slug: trello-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-plugins-api-openapi.yml
- filename: trello-search-api-openapi.yml
  format: yaml
  label: trello Search API
  slug: trello-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-search-api-openapi.yml
- filename: trello-tokens-api-openapi.yml
  format: yaml
  label: trello Tokens API
  slug: trello-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-tokens-api-openapi.yml
- filename: trello-webhooks-api-openapi.yml
  format: yaml
  label: trello Webhooks API
  slug: trello-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-webhooks-api-openapi.yml
- filename: trello-applications-api-openapi.yml
  format: yaml
  label: Trello Applications API
  slug: trello-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-applications-api-openapi.yml
- filename: trello-batch-api-openapi.yml
  format: yaml
  label: Trello Batch API
  slug: trello-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-batch-api-openapi.yml
- filename: trello-emoji-api-openapi.yml
  format: yaml
  label: Trello Emoji API
  slug: trello-emoji-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-emoji-api-openapi.yml
- filename: trello-enterprises-api-openapi.yml
  format: yaml
  label: Trello Enterprises API
  slug: trello-enterprises-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-enterprises-api-openapi.yml
- filename: trello-custom-fields-api-openapi.yml
  format: yaml
  label: Trello Custom Fields API
  slug: trello-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trello/openapi/trello-custom-fields-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Customer ” means the entity on behalf of which this Agreement is accepted
    type: business
  - text: or, if that does not apply, the individual accepting this Agreement.
    type: individual
  minimum_age:
    text: The Products are not intended for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Protected health information
    text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products to process) any patient, medical or other protected health information regulated by the Health Insurance Portability and Accountability Act.
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
name: Trello
provenance_date: '2026-11-10'
provider_name: Trello
provider_slug: trello
slug: trello-eligibility
source_date: '2026-11-10'
source_filename: trello-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlassian.com/legal/atlassian-customer-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trello\naid: trello\nurl: https://www.atlassian.com/legal/atlassian-customer-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Customer ” means the entity on behalf of which this Agreement is accepted\n- type: individual\n  text: or, if that does not apply, the individual accepting this Agreement.\nrestricted_uses:\n- summary: Protected health information\n  text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products\n    to process) any patient, medical or other protected\
  \ health information regulated by the Health Insurance Portability\n    and Accountability Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Products are not intended for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/trello/eligibility/trello-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Trello's own page on 2026-11-10.
synthetic: false
tags:
- Project Management
- Kanban
- Task Management
- Collaboration
- Productivity
- Workflows
- Boards
- Atlassian
---
