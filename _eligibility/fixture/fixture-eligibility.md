---
api_specs:
- filename: fixture-accounts-api-openapi.yml
  format: yaml
  label: Fixture Accounts API
  slug: fixture-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-accounts-api-openapi.yml
- filename: fixture-activities-api-openapi.yml
  format: yaml
  label: Fixture Activities API
  slug: fixture-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-activities-api-openapi.yml
- filename: fixture-contacts-api-openapi.yml
  format: yaml
  label: Fixture Contacts API
  slug: fixture-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-contacts-api-openapi.yml
- filename: fixture-deals-api-openapi.yml
  format: yaml
  label: Fixture Deals API
  slug: fixture-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-deals-api-openapi.yml
- filename: fixture-fixture-api-api-openapi.yml
  format: yaml
  label: Fixture API
  slug: fixture-fixture-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-fixture-api-api-openapi.yml
- filename: fixture-leads-api-openapi.yml
  format: yaml
  label: Fixture Leads API
  slug: fixture-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-leads-api-openapi.yml
- filename: fixture-notes-api-openapi.yml
  format: yaml
  label: Fixture Notes API
  slug: fixture-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-notes-api-openapi.yml
- filename: fixture-pipelines-api-openapi.yml
  format: yaml
  label: Fixture Pipelines API
  slug: fixture-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-pipelines-api-openapi.yml
- filename: fixture-task-statuses-api-openapi.yml
  format: yaml
  label: Fixture Task Statuses API
  slug: fixture-task-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-task-statuses-api-openapi.yml
- filename: fixture-tasks-api-openapi.yml
  format: yaml
  label: Fixture Tasks API
  slug: fixture-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-tasks-api-openapi.yml
- filename: fixture-users-api-openapi.yml
  format: yaml
  label: Fixture Users API
  slug: fixture-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-users-api-openapi.yml
- filename: fixture-custom-fields-api-openapi.yml
  format: yaml
  label: Fixture Custom Fields API
  slug: fixture-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-custom-fields-api-openapi.yml
- filename: fixture-lead-lists-api-openapi.yml
  format: yaml
  label: Fixture Lead Lists API
  slug: fixture-lead-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-lead-lists-api-openapi.yml
- filename: fixture-reporting-api-openapi.yml
  format: yaml
  label: Fixture Reporting API
  slug: fixture-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-reporting-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Using the Services only for lawful business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No eligibility determinations
    text: Research results must not be used to determine a person's eligibility for credit, employment, housing, insurance, or similar benefits or services.
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
name: Fixture
provenance_date: '2026-11-09'
provider_name: Fixture
provider_slug: fixture
slug: fixture-eligibility
source_date: '2026-11-09'
source_filename: fixture-eligibility.yml
source_heading: Eligibility
source_page: https://www.fixture.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fixture\naid: fixture\nurl: https://www.fixture.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Using the Services only for lawful business purposes\nrestricted_uses:\n- summary: No eligibility determinations\n  text: Research results must not be used to determine a person's eligibility for credit, employment, housing, insurance,\n    or similar benefits or services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fixture/eligibility/fixture-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Fixture's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Sales
- B2B
- Artificial Intelligence
- Agents
- MCP
---
