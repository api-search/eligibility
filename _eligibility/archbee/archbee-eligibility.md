---
api_specs:
- filename: archbee-access-control-api-openapi.yml
  format: yaml
  label: Archbee Access Control API
  slug: archbee-access-control-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-access-control-api-openapi.yml
- filename: archbee-api-reference-api-openapi.yml
  format: yaml
  label: Archbee API Reference API
  slug: archbee-api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-api-reference-api-openapi.yml
- filename: archbee-documents-api-openapi.yml
  format: yaml
  label: Archbee Documents API
  slug: archbee-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-documents-api-openapi.yml
- filename: archbee-file-manager-api-openapi.yml
  format: yaml
  label: Archbee File Manager API
  slug: archbee-file-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-file-manager-api-openapi.yml
- filename: archbee-members-api-openapi.yml
  format: yaml
  label: Archbee Members API
  slug: archbee-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-members-api-openapi.yml
- filename: archbee-organization-api-openapi.yml
  format: yaml
  label: Archbee Organization API
  slug: archbee-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-organization-api-openapi.yml
- filename: archbee-pages-api-openapi.yml
  format: yaml
  label: Archbee Pages API
  slug: archbee-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-pages-api-openapi.yml
- filename: archbee-space-groups-api-openapi.yml
  format: yaml
  label: Archbee Space Groups API
  slug: archbee-space-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-space-groups-api-openapi.yml
- filename: archbee-spaces-api-openapi.yml
  format: yaml
  label: Archbee Spaces API
  slug: archbee-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-spaces-api-openapi.yml
- filename: archbee-suggestions-api-openapi.yml
  format: yaml
  label: Archbee Suggestions API
  slug: archbee-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archbee/openapi/archbee-suggestions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are a person barred from receiving the Services under the laws of the United States or other countries including the country in which you are resident or from which you use the Services
  minimum_age:
    text: you are not of legal age to form a binding contract with AiurLabs
    value: null
  restricted_uses:
  - summary: No regulated or export-controlled data
    text: you will not, and will use commercially reasonable efforts to make sure a third party does not, use the Services to store or transfer any data that is controlled for export under any export or reexport control law or regulation
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
name: Archbee
provenance_date: '2026-11-09'
provider_name: Archbee
provider_slug: archbee
slug: archbee-eligibility
source_date: '2026-11-09'
source_filename: archbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.archbee.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Archbee\naid: archbee\nurl: https://www.archbee.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are a person barred from receiving the Services under the laws of the United States or other countries\n    including the country in which you are resident or from which you use the Services\nentity_types: []\nrestricted_uses:\n- summary: No regulated or export-controlled data\n  text: you will not, and will use commercially reasonable efforts to make sure a third party does not, use the\n    Services to store or transfer any data that is controlled for export\
  \ under any export or reexport control law\n    or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with AiurLabs\n"
source_yaml_url: https://artifacts.apis.io/archbee/eligibility/archbee-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Archbee's own page on 2026-11-09.
synthetic: false
tags:
- API Documentation
- Documentation Platform
- Knowledge Base
- Technical Writing
- Developer Docs
- Developer Portal
- Docs as Code
- OpenAPI
- MCP
- AI Agents
- Content Management
- Developer Tools
- Documentation
---
