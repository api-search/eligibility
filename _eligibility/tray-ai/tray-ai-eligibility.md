---
api_specs:
- filename: tray-ai-authentication-api-openapi.yml
  format: yaml
  label: Tray.ai Authentication API
  slug: tray-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-authentication-api-openapi.yml
- filename: tray-ai-authentications-api-openapi.yml
  format: yaml
  label: Tray.ai Authentications API
  slug: tray-ai-authentications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-authentications-api-openapi.yml
- filename: tray-ai-call-connector-api-openapi.yml
  format: yaml
  label: Tray.ai Call Connector API
  slug: tray-ai-call-connector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-call-connector-api-openapi.yml
- filename: tray-ai-connectors-api-openapi.yml
  format: yaml
  label: Tray.ai Connectors API
  slug: tray-ai-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-connectors-api-openapi.yml
- filename: tray-ai-deployments-api-openapi.yml
  format: yaml
  label: Tray.ai Deployments API
  slug: tray-ai-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-deployments-api-openapi.yml
- filename: tray-ai-projects-api-openapi.yml
  format: yaml
  label: Tray.ai Projects API
  slug: tray-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-projects-api-openapi.yml
- filename: tray-ai-solution-instances-api-openapi.yml
  format: yaml
  label: Tray.ai Solution Instances API
  slug: tray-ai-solution-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-solution-instances-api-openapi.yml
- filename: tray-ai-solutions-api-openapi.yml
  format: yaml
  label: Tray.ai Solutions API
  slug: tray-ai-solutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-solutions-api-openapi.yml
- filename: tray-ai-triggers-api-openapi.yml
  format: yaml
  label: Tray.ai Triggers API
  slug: tray-ai-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-triggers-api-openapi.yml
- filename: tray-ai-users-api-openapi.yml
  format: yaml
  label: Tray.ai Users API
  slug: tray-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-users-api-openapi.yml
- filename: tray-ai-workflows-api-openapi.yml
  format: yaml
  label: Tray.ai Workflows API
  slug: tray-ai-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-workflows-api-openapi.yml
- filename: tray-ai-workspaces-api-openapi.yml
  format: yaml
  label: Tray.ai Workspaces API
  slug: tray-ai-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-workspaces-api-openapi.yml
- filename: tray-ai-agent-groups-api-openapi.yml
  format: yaml
  label: Tray.ai Agent Groups API
  slug: tray-ai-agent-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-agent-groups-api-openapi.yml
- filename: tray-ai-agent-instances-api-openapi.yml
  format: yaml
  label: Tray.ai Agent Instances API
  slug: tray-ai-agent-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-agent-instances-api-openapi.yml
- filename: tray-ai-permissions-api-openapi.yml
  format: yaml
  label: Tray.ai Permissions API
  slug: tray-ai-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tray-ai/openapi/tray-ai-permissions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU OR THE ENTITY THAT YOU REPRESENT (YOU OR ANY SUCH ENTITY, “CUSTOMER”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: Customer shall not, and shall not permit Users to, access or use the Tray Service in violation of any U.S. export law or regulation.
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
name: Tray.ai
provenance_date: '2026-11-10'
provider_name: Tray.ai
provider_slug: tray-ai
slug: tray-ai-eligibility
source_date: '2026-11-10'
source_filename: tray-ai-eligibility.yml
source_heading: Eligibility
source_page: https://tray.ai/legal/msa/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tray.ai\naid: tray-ai\nurl: https://tray.ai/legal/msa/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU OR THE ENTITY THAT YOU REPRESENT (YOU OR ANY SUCH ENTITY, “CUSTOMER”)\nrestricted_uses:\n- summary: Export law compliance\n  text: Customer shall not, and shall not permit Users to, access or use the Tray Service in violation of any U.S.\n    export law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tray-ai/eligibility/tray-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tray.ai's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Integration
- iPaaS
- AI Agents
- MCP
- Orchestration
- Workflow Automation
- Connectors
- Agent Gateway
- Embedded Integration
- Enterprise Automation
---
