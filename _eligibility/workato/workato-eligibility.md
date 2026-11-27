---
api_specs:
- filename: workato-data-tables-api-openapi.yml
  format: yaml
  label: Workato Data Tables API
  slug: workato-data-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-data-tables-api-openapi.yml
- filename: workato-genies-api-openapi.yml
  format: yaml
  label: Workato Genies API
  slug: workato-genies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-genies-api-openapi.yml
- filename: workato-knowledge-bases-api-openapi.yml
  format: yaml
  label: Workato Knowledge Bases API
  slug: workato-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-knowledge-bases-api-openapi.yml
- filename: workato-mcp-servers-api-openapi.yml
  format: yaml
  label: Workato MCP Servers API
  slug: workato-mcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-mcp-servers-api-openapi.yml
- filename: workato-messages-api-openapi.yml
  format: yaml
  label: Workato Messages API
  slug: workato-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-messages-api-openapi.yml
- filename: workato-policies-api-openapi.yml
  format: yaml
  label: Workato Policies API
  slug: workato-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-policies-api-openapi.yml
- filename: workato-recipes-api-openapi.yml
  format: yaml
  label: Workato Recipes API
  slug: workato-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-recipes-api-openapi.yml
- filename: workato-skills-api-openapi.yml
  format: yaml
  label: Workato Skills API
  slug: workato-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-skills-api-openapi.yml
- filename: workato-tools-api-openapi.yml
  format: yaml
  label: Workato Tools API
  slug: workato-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-tools-api-openapi.yml
- filename: workato-user-groups-api-openapi.yml
  format: yaml
  label: Workato User Groups API
  slug: workato-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workato/openapi/workato-user-groups-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Account Holder’s use will not be from any sanctioned, embargoed, prohibited, or unauthorized country where Workato cannot provide or is prohibited from providing access.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk systems
    text: for any system or application in which the failure of the Workato Platform could create a risk of personal injury or death, such as medical systems, life sustaining or life-saving systems, transportation systems, or nuclear systems
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
name: Workato
provenance_date: '2026-11-10'
provider_name: Workato
provider_slug: workato
slug: workato-eligibility
source_date: '2026-11-10'
source_filename: workato-eligibility.yml
source_heading: Eligibility
source_page: https://www.workato.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workato\naid: workato\nurl: https://www.workato.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Account Holder’s use will not be from any sanctioned, embargoed, prohibited, or unauthorized country where\n    Workato cannot provide or is prohibited from providing access.\nentity_types: []\nrestricted_uses:\n- summary: High-risk systems\n  text: for any system or application in which the failure of the Workato Platform could create a risk of personal\n    injury or death, such as medical systems, life sustaining or life-saving systems,\
  \ transportation systems, or\n    nuclear systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workato/eligibility/workato-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Workato's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- API Management
- Automation
- B2B
- Embedded iPaaS
- Enterprise
- Integration
- iPaaS
- Orchestration
- Workflows
- Workflow Automation
---
