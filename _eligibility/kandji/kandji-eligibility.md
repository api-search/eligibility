---
api_specs:
- filename: kandji-audit-api-openapi.yml
  format: yaml
  label: Iru Audit API
  slug: kandji-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-audit-api-openapi.yml
- filename: kandji-behavioral-detections-api-openapi.yml
  format: yaml
  label: Iru Behavioral Detections API
  slug: kandji-behavioral-detections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-behavioral-detections-api-openapi.yml
- filename: kandji-blueprints-api-openapi.yml
  format: yaml
  label: Iru Blueprints API
  slug: kandji-blueprints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-blueprints-api-openapi.yml
- filename: kandji-devices-api-openapi.yml
  format: yaml
  label: Iru Devices API
  slug: kandji-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-devices-api-openapi.yml
- filename: kandji-integrations-api-openapi.yml
  format: yaml
  label: Iru Integrations API
  slug: kandji-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-integrations-api-openapi.yml
- filename: kandji-library-api-openapi.yml
  format: yaml
  label: Iru Library API
  slug: kandji-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-library-api-openapi.yml
- filename: kandji-prism-api-openapi.yml
  format: yaml
  label: Iru Prism API
  slug: kandji-prism-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-prism-api-openapi.yml
- filename: kandji-self-service-api-openapi.yml
  format: yaml
  label: Iru Self Service API
  slug: kandji-self-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-self-service-api-openapi.yml
- filename: kandji-settings-api-openapi.yml
  format: yaml
  label: Iru Settings API
  slug: kandji-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-settings-api-openapi.yml
- filename: kandji-tags-api-openapi.yml
  format: yaml
  label: Iru Tags API
  slug: kandji-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-tags-api-openapi.yml
- filename: kandji-threat-details-api-openapi.yml
  format: yaml
  label: Iru Threat Details API
  slug: kandji-threat-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-threat-details-api-openapi.yml
- filename: kandji-upload-to-s3-api-openapi.yml
  format: yaml
  label: Iru Upload To S3 API
  slug: kandji-upload-to-s3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-upload-to-s3-api-openapi.yml
- filename: kandji-users-api-openapi.yml
  format: yaml
  label: Iru Users API
  slug: kandji-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-users-api-openapi.yml
- filename: kandji-vulnerability-management-api-openapi.yml
  format: yaml
  label: Iru Vulnerability Management API
  slug: kandji-vulnerability-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kandji/openapi/kandji-vulnerability-management-api-openapi.yml
- filename: how-to-set-up-the-iru-endpoint-api-in-postman.md
  format: yaml
  label: Iru Endpoint Management API
  slug: iru-endpoint-management-api
  spec_type: Postman
  url: https://docs.iru.com/en/endpoint/api/how-to-set-up-the-iru-endpoint-api-in-postman.md
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Licensee will not permit any User to access or use any Services in a U.S.-embargoed country or region (currently Cuba, Iran, North Korea, Syria or Crimea)
  entity_types:
  - text: THIS PLATFORM SERVICES AGREEMENT (“AGREEMENT”) IS A LEGALLY BINDING CONTRACT BETWEEN YOU, ON BEHALF OF THE LEGAL ENTITY YOU REPRESENT (“LICENSEE”)
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Iru
provenance_date: '2026-11-09'
provider_name: Iru
provider_slug: kandji
slug: kandji-eligibility
source_date: '2026-11-09'
source_filename: kandji-eligibility.yml
source_heading: Eligibility
source_page: https://www.iru.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iru\naid: kandji\nurl: https://www.iru.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Licensee will not permit any User to access or use any Services in a U.S.-embargoed country or region (currently\n    Cuba, Iran, North Korea, Syria or Crimea)\nentity_types:\n- type: business\n  text: THIS PLATFORM SERVICES AGREEMENT (“AGREEMENT”) IS A LEGALLY BINDING CONTRACT BETWEEN YOU, ON BEHALF OF THE\n    LEGAL ENTITY YOU REPRESENT (“LICENSEE”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kandji/eligibility/kandji-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Iru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Device Management
- Mobile Device Management
- apple-management
- Endpoint Security
- Endpoint Detection and Response
- Vulnerability Management
- Compliance Automation
- Workforce Identity
- IT Operations
- MCP
- Agent-Native
---
