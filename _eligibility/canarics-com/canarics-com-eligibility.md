---
api_specs:
- filename: canarics-com-agents-api-openapi.yml
  format: yaml
  label: canarics-com Agents API
  slug: canarics-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-agents-api-openapi.yml
- filename: canarics-com-callbacks-api-openapi.yml
  format: yaml
  label: canarics-com Callbacks API
  slug: canarics-com-callbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-callbacks-api-openapi.yml
- filename: canarics-com-calls-api-openapi.yml
  format: yaml
  label: canarics-com Calls API
  slug: canarics-com-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-calls-api-openapi.yml
- filename: canarics-com-campaigns-api-openapi.yml
  format: yaml
  label: canarics-com Campaigns API
  slug: canarics-com-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-campaigns-api-openapi.yml
- filename: canarics-com-canarics-api-for-ai-agents-api-openapi.yml
  format: yaml
  label: canarics-com Canarics API For AI Agents API
  slug: canarics-com-canarics-api-for-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-canarics-api-for-ai-agents-api-openapi.yml
- filename: canarics-com-contacts-api-openapi.yml
  format: yaml
  label: canarics-com Contacts API
  slug: canarics-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-contacts-api-openapi.yml
- filename: canarics-com-conversations-api-openapi.yml
  format: yaml
  label: canarics-com Conversations API
  slug: canarics-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-conversations-api-openapi.yml
- filename: canarics-com-demo-call-api-openapi.yml
  format: yaml
  label: canarics-com Demo Call API
  slug: canarics-com-demo-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-demo-call-api-openapi.yml
- filename: canarics-com-mcp-api-openapi.yml
  format: yaml
  label: canarics-com MCP API
  slug: canarics-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-mcp-api-openapi.yml
- filename: canarics-com-me-api-openapi.yml
  format: yaml
  label: canarics-com Me API
  slug: canarics-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-me-api-openapi.yml
- filename: canarics-com-signup-api-openapi.yml
  format: yaml
  label: canarics-com Signup API
  slug: canarics-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-signup-api-openapi.yml
- filename: canarics-com-tools-api-openapi.yml
  format: yaml
  label: canarics-com Tools API
  slug: canarics-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-tools-api-openapi.yml
- filename: canarics-com-upgrade-api-openapi.yml
  format: yaml
  label: canarics-com Upgrade API
  slug: canarics-com-upgrade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-upgrade-api-openapi.yml
- filename: canarics-com-usage-api-openapi.yml
  format: yaml
  label: canarics-com Usage API
  slug: canarics-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canarics-com/openapi/canarics-com-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Demo calls are currently available to European numbers only.
  entity_types:
  - text: Canarics is a B2B tool for sales, support, and reception teams.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Emergency calls
    text: CANNOT be used to place or route emergency calls to 112, 911, or any other emergency service.
  - summary: Abusive automated calling
    text: such as automated robocalling, telemarketing spam, or usage significantly exceeding typical business human behavior.
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
name: canarics-com
provenance_date: '2026-11-09'
provider_name: canarics-com
provider_slug: canarics-com
slug: canarics-com-eligibility
source_date: '2026-11-09'
source_filename: canarics-com-eligibility.yml
source_heading: Eligibility
source_page: https://canarics.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: canarics-com\naid: canarics-com\nurl: https://canarics.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Demo calls are currently available to European numbers only.\nentity_types:\n- type: business\n  text: Canarics is a B2B tool for sales, support, and reception teams.\nrestricted_uses:\n- summary: Emergency calls\n  text: CANNOT be used to place or route emergency calls to 112, 911, or any other emergency service.\n- summary: Abusive automated calling\n  text: such as automated robocalling, telemarketing spam, or usage significantly exceeding typical business human\n\
  \    behavior.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canarics-com/eligibility/canarics-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from canarics-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice
- Sales Intelligence
- Enterprise
---
