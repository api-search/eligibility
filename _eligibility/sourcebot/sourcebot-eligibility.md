---
api_specs:
- filename: sourcebot-enterprise-ee-api-openapi.yml
  format: yaml
  label: Sourcebot Enterprise (EE) API
  slug: sourcebot-enterprise-ee-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-enterprise-ee-api-openapi.yml
- filename: sourcebot-git-api-openapi.yml
  format: yaml
  label: Sourcebot Git API
  slug: sourcebot-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-git-api-openapi.yml
- filename: sourcebot-repositories-api-openapi.yml
  format: yaml
  label: Sourcebot Repositories API
  slug: sourcebot-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-repositories-api-openapi.yml
- filename: sourcebot-search-navigation-api-openapi.yml
  format: yaml
  label: Sourcebot Search & Navigation API
  slug: sourcebot-search-navigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-search-navigation-api-openapi.yml
- filename: sourcebot-system-api-openapi.yml
  format: yaml
  label: Sourcebot System API
  slug: sourcebot-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcebot/openapi/sourcebot-system-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that it is not located in, or a resident or national of, any country subject to U.S. trade sanctions
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Heightened regulatory data
    text: input, upload, transmit, or process through the Software any data that is subject to heightened regulatory requirements (including protected health information under HIPAA, payment card data subject to PCI DSS
  - summary: Sanctioned jurisdictions
    text: access, install, or use the Software in, or export, re-export, or transfer the Software to, any country, region, or party subject to U.S., EU, U.K., or other applicable trade sanctions
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
name: Sourcebot
provenance_date: '2026-11-10'
provider_name: Sourcebot
provider_slug: sourcebot
slug: sourcebot-eligibility
source_date: '2026-11-10'
source_filename: sourcebot-eligibility.yml
source_heading: Eligibility
source_page: https://www.sourcebot.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sourcebot\naid: sourcebot\nurl: https://www.sourcebot.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that it is not located in, or a resident or national of, any country subject to U.S.\n    trade sanctions\nentity_types: []\nrestricted_uses:\n- summary: Heightened regulatory data\n  text: input, upload, transmit, or process through the Software any data that is subject to heightened regulatory\n    requirements (including protected health information under HIPAA, payment card data subject to PCI DSS\n- summary: Sanctioned jurisdictions\n  text: access,\
  \ install, or use the Software in, or export, re-export, or transfer the Software to, any country,\n    region, or party subject to U.S., EU, U.K., or other applicable trade sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sourcebot/eligibility/sourcebot-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Sourcebot's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Search
- Code Intelligence
- Developer Tools
- Source Code
- Version Control
- MCP
- AI Coding Agents
- Enterprise Search
- Self-Hosted
---
