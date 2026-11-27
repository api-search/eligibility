---
api_specs:
- filename: axiorank-com-audit-api-openapi.yml
  format: yaml
  label: AxioRank Audit API
  slug: axiorank-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-audit-api-openapi.yml
- filename: axiorank-com-gateway-api-openapi.yml
  format: yaml
  label: AxioRank Gateway API
  slug: axiorank-com-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-gateway-api-openapi.yml
- filename: axiorank-com-health-api-openapi.yml
  format: yaml
  label: AxioRank Health API
  slug: axiorank-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-health-api-openapi.yml
- filename: axiorank-com-mcp-api-openapi.yml
  format: yaml
  label: AxioRank MCP API
  slug: axiorank-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-mcp-api-openapi.yml
- filename: axiorank-com-protocols-api-openapi.yml
  format: yaml
  label: AxioRank Protocols API
  slug: axiorank-com-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-protocols-api-openapi.yml
- filename: axiorank-com-tools-log-api-openapi.yml
  format: yaml
  label: AxioRank Tools Log API
  slug: axiorank-com-tools-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiorank-com/openapi/axiorank-com-tools-log-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in an embargoed jurisdiction or on a restricted-party list.
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that organization to these Terms, and “you” refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: use the Service in violation of any applicable law, regulation, or third-party right
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
name: AxioRank
provenance_date: '2026-11-09'
provider_name: AxioRank
provider_slug: axiorank-com
slug: axiorank-com-eligibility
source_date: '2026-11-09'
source_filename: axiorank-com-eligibility.yml
source_heading: Eligibility
source_page: https://axiorank.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AxioRank\naid: axiorank-com\nurl: https://axiorank.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in an embargoed jurisdiction or on a restricted-party list.\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that\n    organization to these Terms, and “you” refers to that organization.\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: use the Service in violation of any applicable law, regulation, or third-party right\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/axiorank-com/eligibility/axiorank-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AxioRank's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Security
- Gateways
- Zero Trust
- Agents
---
