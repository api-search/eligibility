---
api_specs:
- filename: agent-native-com-desktop-api-openapi.yml
  format: yaml
  label: agent-native-com Desktop API
  slug: agent-native-com-desktop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-native-com/openapi/agent-native-com-desktop-api-openapi.yml
- filename: agent-native-com-mcp-api-openapi.yml
  format: yaml
  label: agent-native-com MCP API
  slug: agent-native-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-native-com/openapi/agent-native-com-mcp-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer is not located in, organized under the laws of, or owned or controlled by any person or entity subject to sanctions administered by the U.S. Office of Foreign Assets Control (OFAC) or any other applicable sanctions authority;
  entity_types:
  - text: The person or entity accessing or using the Service is referred to as "you" or "Customer."
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated and age-restricted services
    text: You may operate Hosted Applications offering regulated or age-restricted goods or services, including gambling, financial services, alcohol, tobacco, weapons, or controlled substances, only if you maintain all licenses, certifications, and approvals required by applicable law.
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
name: agent-native-com
provenance_date: '2026-11-09'
provider_name: agent-native-com
provider_slug: agent-native-com
slug: agent-native-com-eligibility
source_date: '2026-11-09'
source_filename: agent-native-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.agent-native.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agent-native-com\naid: agent-native-com\nurl: https://www.agent-native.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer is not located in, organized under the laws of, or owned or controlled by any person or entity\n    subject to sanctions administered by the U.S. Office of Foreign Assets Control (OFAC) or any other applicable\n    sanctions authority;\nentity_types:\n- type: individual\n  text: The person or entity accessing or using the Service is referred to as \"you\" or \"Customer.\"\nrestricted_uses:\n- summary: Regulated and age-restricted services\n  text:\
  \ You may operate Hosted Applications offering regulated or age-restricted goods or services, including gambling,\n    financial services, alcohol, tobacco, weapons, or controlled substances, only if you maintain all licenses,\n    certifications, and approvals required by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agent-native-com/eligibility/agent-native-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from agent-native-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Framework
- Open Source
- Developer Tools
---
