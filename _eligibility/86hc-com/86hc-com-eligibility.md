---
api_specs:
- filename: 86hc-com-openapi.json
  format: json
  label: Hong Kong Company MCP & Corporate Registry API
  slug: hong-kong-company-mcp-corporate-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/86hc-com/openapi/86hc-com-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 如您为自然人，您已 年满 18 周岁 并具备完全民事行为能力以独立承担法律责任
    type: individual
  - text: 如您代表任何法团、律师事务所、金融机构或其他组织行事，您已获该实体之充分合法授权，使该实体受本协议之约束
    type: business
  minimum_age:
    text: 您已 年满 18 周岁 并具备完全民事行为能力以独立承担法律责任
    value: '18'
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
name: 恒诚
provenance_date: '2026-11-09'
provider_name: 恒诚
provider_slug: 86hc-com
slug: 86hc-com-eligibility
source_date: '2026-11-09'
source_filename: 86hc-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.86hc.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 恒诚\naid: 86hc-com\nurl: https://www.86hc.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 如您为自然人，您已 年满 18 周岁 并具备完全民事行为能力以独立承担法律责任\n- type: business\n  text: 如您代表任何法团、律师事务所、金融机构或其他组织行事，您已获该实体之充分合法授权，使该实体受本协议之约束\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 您已 年满 18 周岁 并具备完全民事行为能力以独立承担法律责任\n"
source_yaml_url: https://artifacts.apis.io/86hc-com/eligibility/86hc-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from 恒诚's own page on 2026-11-09.
synthetic: false
tags:
- Hong Kong
- Business Intelligence
- Due Diligence
- Corporate Services
- Compliance
---
