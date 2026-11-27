---
api_specs:
- filename: yutori-browsing-api-openapi.yml
  format: yaml
  label: Yutori Browsing API
  slug: yutori-browsing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-browsing-api-openapi.yml
- filename: yutori-chat-completions-api-openapi.yml
  format: yaml
  label: Yutori Chat Completions API
  slug: yutori-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-chat-completions-api-openapi.yml
- filename: yutori-health-api-openapi.yml
  format: yaml
  label: Yutori Health API
  slug: yutori-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-health-api-openapi.yml
- filename: yutori-research-api-openapi.yml
  format: yaml
  label: Yutori Research API
  slug: yutori-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-research-api-openapi.yml
- filename: yutori-scouting-api-openapi.yml
  format: yaml
  label: Yutori Scouting API
  slug: yutori-scouting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yutori/openapi/yutori-scouting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Regulated-industry data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Yutori
provenance_date: '2026-11-10'
provider_name: Yutori
provider_slug: yutori
slug: yutori-eligibility
source_date: '2026-11-10'
source_filename: yutori-eligibility.yml
source_heading: Eligibility
source_page: https://yutori.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yutori\naid: yutori\nurl: https://yutori.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Regulated-industry data\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such\
  \ laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/yutori/eligibility/yutori-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Yutori's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Browser Automation
- Web Monitoring
- Research
- MCP
- LLM
- Foundation Models
---
