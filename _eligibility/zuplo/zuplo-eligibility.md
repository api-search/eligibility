---
api_specs:
- filename: zuplo-api-keys-buckets-api-openapi.yml
  format: yaml
  label: Zuplo API Keys - Buckets API
  slug: zuplo-api-keys-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-api-keys-buckets-api-openapi.yml
- filename: zuplo-api-keys-consumers-api-openapi.yml
  format: yaml
  label: Zuplo API Keys - Consumers API
  slug: zuplo-api-keys-consumers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-api-keys-consumers-api-openapi.yml
- filename: zuplo-api-keys-keys-api-openapi.yml
  format: yaml
  label: Zuplo API Keys - Keys API
  slug: zuplo-api-keys-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-api-keys-keys-api-openapi.yml
- filename: zuplo-api-keys-managers-api-openapi.yml
  format: yaml
  label: Zuplo API Keys - Managers API
  slug: zuplo-api-keys-managers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-api-keys-managers-api-openapi.yml
- filename: zuplo-audit-logs-api-openapi.yml
  format: yaml
  label: Zuplo Audit Logs API
  slug: zuplo-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-audit-logs-api-openapi.yml
- filename: zuplo-custom-domains-api-openapi.yml
  format: yaml
  label: Zuplo Custom Domains API
  slug: zuplo-custom-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-custom-domains-api-openapi.yml
- filename: zuplo-deployments-api-openapi.yml
  format: yaml
  label: Zuplo Deployments API
  slug: zuplo-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-deployments-api-openapi.yml
- filename: zuplo-mcp-servers-api-openapi.yml
  format: yaml
  label: Zuplo MCP Servers API
  slug: zuplo-mcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-mcp-servers-api-openapi.yml
- filename: zuplo-tunnel-services-api-openapi.yml
  format: yaml
  label: Zuplo Tunnel Services API
  slug: zuplo-tunnel-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-tunnel-services-api-openapi.yml
- filename: zuplo-tunnels-api-openapi.yml
  format: yaml
  label: Zuplo Tunnels API
  slug: zuplo-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-tunnels-api-openapi.yml
- filename: zuplo-variables-api-openapi.yml
  format: yaml
  label: Zuplo Variables API
  slug: zuplo-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-variables-api-openapi.yml
- filename: zuplo-open-api-api-openapi.yml
  format: yaml
  label: Zuplo Open API
  slug: zuplo-open-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-open-api-api-openapi.yml
- filename: zuplo-whoami-api-openapi.yml
  format: yaml
  label: Zuplo Whoami API
  slug: zuplo-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zuplo/openapi/zuplo-whoami-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Customer: The company or person who accesses or uses the Product. If the person accepting this Agreement is doing so on behalf of a company, all use of the word “Customer” in the Agreement will mean that company.'
    type: business
  - text: 'Customer: The company or person who accesses or uses the Product.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: HIPAA data only under BAA
    text: Customer may submit Prohibited Data to the Product, except protected health information regulated by the Health Insurance Portability and Accountability Act (“HIPAA”), which Customer may submit only under a Business Associate Agreement signed with Provider.
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
name: Zuplo
provenance_date: '2026-11-10'
provider_name: Zuplo
provider_slug: zuplo
slug: zuplo-eligibility
source_date: '2026-11-10'
source_filename: zuplo-eligibility.yml
source_heading: Eligibility
source_page: https://zuplo.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zuplo\naid: zuplo\nurl: https://zuplo.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Customer: The company or person who accesses or uses the Product. If the person accepting this Agreement\n    is doing so on behalf of a company, all use of the word “Customer” in the Agreement will mean that company.'\n- type: individual\n  text: 'Customer: The company or person who accesses or uses the Product.'\nrestricted_uses:\n- summary: HIPAA data only under BAA\n  text: Customer may submit Prohibited Data to the Product, except\
  \ protected health information regulated by the\n    Health Insurance Portability and Accountability Act (“HIPAA”), which Customer may submit only under a Business\n    Associate Agreement signed with Provider.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zuplo/eligibility/zuplo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Zuplo's own page on 2026-11-10.
synthetic: false
tags:
- AI Gateway
- API Management
- Gateways
- Platform
- API Gateway
- MCP Gateway
- Authentication
- Rate Limiting
- Spend Management
- Developer Tools
---
