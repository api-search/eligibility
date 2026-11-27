---
api_specs:
- filename: budibase-applications-api-openapi.yml
  format: yaml
  label: Budibase Applications API
  slug: budibase-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-applications-api-openapi.yml
- filename: budibase-queries-api-openapi.yml
  format: yaml
  label: Budibase Queries API
  slug: budibase-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-queries-api-openapi.yml
- filename: budibase-rows-api-openapi.yml
  format: yaml
  label: Budibase Rows API
  slug: budibase-rows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-rows-api-openapi.yml
- filename: budibase-tables-api-openapi.yml
  format: yaml
  label: Budibase Tables API
  slug: budibase-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-tables-api-openapi.yml
- filename: budibase-users-api-openapi.yml
  format: yaml
  label: Budibase Users API
  slug: budibase-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-users-api-openapi.yml
- filename: budibase-metrics-api-openapi.yml
  format: yaml
  label: Budibase Metrics API
  slug: budibase-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-metrics-api-openapi.yml
- filename: budibase-roles-api-openapi.yml
  format: yaml
  label: Budibase Roles API
  slug: budibase-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-roles-api-openapi.yml
- filename: budibase-views-api-openapi.yml
  format: yaml
  label: Budibase Views API
  slug: budibase-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-views-api-openapi.yml
- filename: budibase-workspaces-api-openapi.yml
  format: yaml
  label: Budibase Workspaces API
  slug: budibase-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budibase/openapi/budibase-workspaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: where Customer is or purports to represent an organisation or entity, Customer (including the person entering into the Agreement on Customer’s behalf in their individual capacity) warrants and represents that it or they is/are entitled to act in this capacity
    type: business
  minimum_age:
    text: Authorised Users (who must be aged 18 or over the legally required age in the country in which they live and to whose laws they are subject to use the Subscription Services)
    value: '18'
  restricted_uses:
  - summary: No sensitive information
    text: CUSTOMER AGREES NOT TO USE THE SUBSCRIPTION SERVICES TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION.
  - summary: No automated accounts without a responsible human
    text: operate a service or automated account, where there is not a single human individual responsible for that account
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
name: Budibase
provenance_date: '2026-11-09'
provider_name: Budibase
provider_slug: budibase
slug: budibase-eligibility
source_date: '2026-11-09'
source_filename: budibase-eligibility.yml
source_heading: Eligibility
source_page: https://budibase.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Budibase\naid: budibase\nurl: https://budibase.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: where Customer is or purports to represent an organisation or entity, Customer (including the person entering\n    into the Agreement on Customer’s behalf in their individual capacity) warrants and represents that it or they\n    is/are entitled to act in this capacity\nrestricted_uses:\n- summary: No sensitive information\n  text: CUSTOMER AGREES NOT TO USE THE SUBSCRIPTION SERVICES TO COLLECT, MANAGE OR PROCESS\
  \ SENSITIVE INFORMATION.\n- summary: No automated accounts without a responsible human\n  text: operate a service or automated account, where there is not a single human individual responsible for that\n    account\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Authorised Users (who must be aged 18 or over the legally required age in the country in which they live\n    and to whose laws they are subject to use the Subscription Services)\n"
source_yaml_url: https://artifacts.apis.io/budibase/eligibility/budibase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Budibase's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Automation
- Internal Tools
- Low-Code
- Open Source
- Workflow Automation
---
