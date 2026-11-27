---
api_specs:
- filename: aptly-app-api-openapi.yml
  format: yaml
  label: Aptly App API
  slug: aptly-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-app-api-openapi.yml
- filename: aptly-board-api-openapi.yml
  format: yaml
  label: Aptly Board API
  slug: aptly-board-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-board-api-openapi.yml
- filename: aptly-boards-api-openapi.yml
  format: yaml
  label: Aptly Boards API
  slug: aptly-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-boards-api-openapi.yml
- filename: aptly-cards-api-openapi.yml
  format: yaml
  label: Aptly Cards API
  slug: aptly-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-cards-api-openapi.yml
- filename: aptly-company-api-openapi.yml
  format: yaml
  label: Aptly Company API
  slug: aptly-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-company-api-openapi.yml
- filename: aptly-contacts-api-openapi.yml
  format: yaml
  label: Aptly Contacts API
  slug: aptly-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-contacts-api-openapi.yml
- filename: aptly-email-api-openapi.yml
  format: yaml
  label: Aptly Email API
  slug: aptly-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-email-api-openapi.yml
- filename: aptly-files-api-openapi.yml
  format: yaml
  label: Aptly Files API
  slug: aptly-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-files-api-openapi.yml
- filename: aptly-inboxes-api-openapi.yml
  format: yaml
  label: Aptly Inboxes API
  slug: aptly-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-inboxes-api-openapi.yml
- filename: aptly-knowledge-api-openapi.yml
  format: yaml
  label: Aptly Knowledge API
  slug: aptly-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-knowledge-api-openapi.yml
- filename: aptly-routinggroups-api-openapi.yml
  format: yaml
  label: Aptly RoutingGroups API
  slug: aptly-routinggroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-routinggroups-api-openapi.yml
- filename: aptly-schema-api-openapi.yml
  format: yaml
  label: Aptly Schema API
  slug: aptly-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-schema-api-openapi.yml
- filename: aptly-tasks-api-openapi.yml
  format: yaml
  label: Aptly Tasks API
  slug: aptly-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-tasks-api-openapi.yml
- filename: aptly-templates-api-openapi.yml
  format: yaml
  label: Aptly Templates API
  slug: aptly-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-templates-api-openapi.yml
- filename: aptly-users-api-openapi.yml
  format: yaml
  label: Aptly Users API
  slug: aptly-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-users-api-openapi.yml
- filename: aptly-docs-api-openapi.yml
  format: yaml
  label: Aptly Docs API
  slug: aptly-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-docs-api-openapi.yml
- filename: aptly-tours-api-openapi.yml
  format: yaml
  label: Aptly Tours API
  slug: aptly-tours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-tours-api-openapi.yml
- filename: aptly-webforms-api-openapi.yml
  format: yaml
  label: Aptly Web Forms API
  slug: aptly-webforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptly/openapi/aptly-webforms-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: we provide renter screening services that enable our third-party landlord and property management clients (each, a " Client ")
    type: business
  minimum_age:
    text: Our Platform is not intended for those under the age of 18 — if you access our Platform, you represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Data limited to renter evaluation
    text: you will use all data, analysis and other information you learn about Renters through your use of the Site (" Data ") for legal internal business purposes only to properly evaluate the qualifications of Renters
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
name: Aptly
provenance_date: '2026-11-09'
provider_name: Aptly
provider_slug: aptly
slug: aptly-eligibility
source_date: '2026-11-09'
source_filename: aptly-eligibility.yml
source_heading: Eligibility
source_page: https://www.getaptly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aptly\naid: aptly\nurl: https://www.getaptly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: we provide renter screening services that enable our third-party landlord and property management clients\n    (each, a \" Client \")\nrestricted_uses:\n- summary: Data limited to renter evaluation\n  text: you will use all data, analysis and other information you learn about Renters through your use of the Site\n    (\" Data \") for legal internal business purposes only to properly evaluate the qualifications of Renters\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Platform is not intended for those under the age of 18 — if you access our Platform, you represent and\n    warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/aptly/eligibility/aptly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aptly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- Property Management
- Real Estate
- PropTech
- CRM
- Workflow Automation
- AI Agents
- Communications
- MCP
---
