---
api_specs:
- filename: atomicwork-assets-api-openapi.yml
  format: yaml
  label: Atomicwork Assets API
  slug: atomicwork-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-assets-api-openapi.yml
- filename: atomicwork-businesshourconfig-api-openapi.yml
  format: yaml
  label: Atomicwork Business Hour Config API
  slug: atomicwork-businesshourconfig-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-businesshourconfig-api-openapi.yml
- filename: atomicwork-entities-api-openapi.yml
  format: yaml
  label: Atomicwork Entities API
  slug: atomicwork-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-entities-api-openapi.yml
- filename: atomicwork-forms-api-openapi.yml
  format: yaml
  label: Atomicwork Forms API
  slug: atomicwork-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-forms-api-openapi.yml
- filename: atomicwork-problems-api-openapi.yml
  format: yaml
  label: Atomicwork Problems API
  slug: atomicwork-problems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-problems-api-openapi.yml
- filename: atomicwork-requests-api-openapi.yml
  format: yaml
  label: Atomicwork Requests API
  slug: atomicwork-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-requests-api-openapi.yml
- filename: atomicwork-tags-api-openapi.yml
  format: yaml
  label: Atomicwork Tags API
  slug: atomicwork-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-tags-api-openapi.yml
- filename: atomicwork-users-api-openapi.yml
  format: yaml
  label: Atomicwork Users API
  slug: atomicwork-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-users-api-openapi.yml
- filename: atomicwork-workflows-api-openapi.yml
  format: yaml
  label: Atomicwork Workflows API
  slug: atomicwork-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-workflows-api-openapi.yml
- filename: atomicwork-workspaces-api-openapi.yml
  format: yaml
  label: Atomicwork Workspaces API
  slug: atomicwork-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-workspaces-api-openapi.yml
- filename: atomicwork-assignees-api-openapi.yml
  format: yaml
  label: Atomicwork Assignees API
  slug: atomicwork-assignees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-assignees-api-openapi.yml
- filename: atomicwork-importjobs-api-openapi.yml
  format: yaml
  label: Atomicwork Import Jobs API
  slug: atomicwork-importjobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-importjobs-api-openapi.yml
- filename: atomicwork-access-management-api-openapi.yml
  format: yaml
  label: Atomicwork Access Management API
  slug: atomicwork-access-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-access-management-api-openapi.yml
- filename: atomicwork-agent-groups-api-openapi.yml
  format: yaml
  label: Atomicwork Agent Groups API
  slug: atomicwork-agent-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-agent-groups-api-openapi.yml
- filename: atomicwork-audit-logs-api-openapi.yml
  format: yaml
  label: Atomicwork Audit Logs API
  slug: atomicwork-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-audit-logs-api-openapi.yml
- filename: atomicwork-change-management-api-openapi.yml
  format: yaml
  label: Atomicwork Change Management API
  slug: atomicwork-change-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-change-management-api-openapi.yml
- filename: atomicwork-custom-objects-api-openapi.yml
  format: yaml
  label: Atomicwork Custom Objects API
  slug: atomicwork-custom-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-custom-objects-api-openapi.yml
- filename: atomicwork-service-catalog-api-openapi.yml
  format: yaml
  label: Atomicwork Service Catalog API
  slug: atomicwork-service-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atomicwork/openapi/atomicwork-service-catalog-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity and its affiliates to these terms and conditions
    type: business
  minimum_age:
    text: (a) are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: are not our competitor, or are not using our Website or Platform for reasons that are in competition with us
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
name: Atomicwork
provenance_date: '2026-11-09'
provider_name: Atomicwork
provider_slug: atomicwork
slug: atomicwork-eligibility
source_date: '2026-11-09'
source_filename: atomicwork-eligibility.yml
source_heading: Eligibility
source_page: https://www.atomicwork.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atomicwork\naid: atomicwork\nurl: https://www.atomicwork.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity and its affiliates to these terms and conditions\nrestricted_uses:\n- summary: Competitors\n  text: are not our competitor, or are not using our Website or Platform for reasons that are in competition with\n    us\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/atomicwork/eligibility/atomicwork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Atomicwork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Service Management
- ITSM
- ESM
- IT Service Desk
- Identity Governance
- Asset Management
- AI Agents
- MCP
- Enterprise
---
