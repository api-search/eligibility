---
api_specs:
- filename: hakuna-absences-api-openapi.yml
  format: yaml
  label: Hakuna Absences API
  slug: hakuna-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-absences-api-openapi.yml
- filename: hakuna-company-api-openapi.yml
  format: yaml
  label: Hakuna Company API
  slug: hakuna-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-company-api-openapi.yml
- filename: hakuna-management-api-openapi.yml
  format: yaml
  label: Hakuna Management API
  slug: hakuna-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-management-api-openapi.yml
- filename: hakuna-organization-api-openapi.yml
  format: yaml
  label: Hakuna Organization API
  slug: hakuna-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-organization-api-openapi.yml
- filename: hakuna-overview-api-openapi.yml
  format: yaml
  label: Hakuna Overview API
  slug: hakuna-overview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-overview-api-openapi.yml
- filename: hakuna-projects-api-openapi.yml
  format: yaml
  label: Hakuna Projects API
  slug: hakuna-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-projects-api-openapi.yml
- filename: hakuna-tasks-api-openapi.yml
  format: yaml
  label: Hakuna Tasks API
  slug: hakuna-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-tasks-api-openapi.yml
- filename: hakuna-time-entries-api-openapi.yml
  format: yaml
  label: Hakuna Time Entries API
  slug: hakuna-time-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-time-entries-api-openapi.yml
- filename: hakuna-timer-api-openapi.yml
  format: yaml
  label: Hakuna Timer API
  slug: hakuna-timer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-timer-api-openapi.yml
- filename: hakuna-users-api-openapi.yml
  format: yaml
  label: Hakuna Users API
  slug: hakuna-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hakuna/openapi/hakuna-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Als Kunde gilt jede natürliche oder juristische Person, welche sich für das oben genannte Angebot registriert hat.
    type: individual
  - text: Als Kunde gilt jede natürliche oder juristische Person, welche sich für das oben genannte Angebot registriert hat.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Hakuna
provenance_date: '2026-11-09'
provider_name: Hakuna
provider_slug: hakuna
slug: hakuna-eligibility
source_date: '2026-11-09'
source_filename: hakuna-eligibility.yml
source_heading: Eligibility
source_page: https://www.hakuna.ch/rechtliches/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hakuna\naid: hakuna\nurl: https://www.hakuna.ch/rechtliches/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Als Kunde gilt jede natürliche oder juristische Person, welche sich für das oben genannte Angebot registriert\n    hat.\n- type: business\n  text: Als Kunde gilt jede natürliche oder juristische Person, welche sich für das oben genannte Angebot registriert\n    hat.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hakuna/eligibility/hakuna-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Hakuna's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Time Tracking
- Human Resources
- Workforce Management
- Absence Management
- Project Tracking
- Software-as-a-Service
- Switzerland
- Small Business
---
