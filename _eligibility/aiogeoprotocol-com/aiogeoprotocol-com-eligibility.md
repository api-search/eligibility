---
api_specs:
- filename: aiogeoprotocol-com-audit-api-openapi.yml
  format: yaml
  label: AIO.GEO Protocol Audit API
  slug: aiogeoprotocol-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiogeoprotocol-com/openapi/aiogeoprotocol-com-audit-api-openapi.yml
- filename: aiogeoprotocol-com-brief-api-openapi.yml
  format: yaml
  label: AIO.GEO Protocol Brief API
  slug: aiogeoprotocol-com-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiogeoprotocol-com/openapi/aiogeoprotocol-com-brief-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not use the Services if prohibited by applicable law, export controls, or sanctions.
  entity_types:
  - text: Agency customers remain responsible for lawful client authorization before auditing third-party domains.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized target systems
    text: You must not use the Services to target systems you do not own or lack authorization to assess.
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
name: AIO.GEO Protocol
provenance_date: '2026-11-09'
provider_name: AIO.GEO Protocol
provider_slug: aiogeoprotocol-com
slug: aiogeoprotocol-com-eligibility
source_date: '2026-11-09'
source_filename: aiogeoprotocol-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aiogeoprotocol.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AIO.GEO Protocol\naid: aiogeoprotocol-com\nurl: https://www.aiogeoprotocol.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not use the Services if prohibited by applicable law, export controls, or sanctions.\nentity_types:\n- type: business\n  text: Agency customers remain responsible for lawful client authorization before auditing third-party domains.\nrestricted_uses:\n- summary: Unauthorized target systems\n  text: You must not use the Services to target systems you do not own or lack authorization to assess.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiogeoprotocol-com/eligibility/aiogeoprotocol-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AIO.GEO Protocol's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- Audit
- Measurements
- CLI
---
