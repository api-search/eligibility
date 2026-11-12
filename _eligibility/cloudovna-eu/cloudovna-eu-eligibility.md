---
api_specs:
- filename: cloudovna-eu-catalog-api-openapi.yml
  format: yaml
  label: Cloudovňa Catalog API
  slug: cloudovna-eu-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-catalog-api-openapi.yml
- filename: cloudovna-eu-health-api-openapi.yml
  format: yaml
  label: Cloudovňa Health API
  slug: cloudovna-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-health-api-openapi.yml
- filename: cloudovna-eu-hooks-api-openapi.yml
  format: yaml
  label: Cloudovňa Hooks API
  slug: cloudovna-eu-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-hooks-api-openapi.yml
- filename: cloudovna-eu-images-api-openapi.yml
  format: yaml
  label: Cloudovňa Images API
  slug: cloudovna-eu-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-images-api-openapi.yml
- filename: cloudovna-eu-integrations-api-openapi.yml
  format: yaml
  label: Cloudovňa Integrations API
  slug: cloudovna-eu-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-integrations-api-openapi.yml
- filename: cloudovna-eu-invitations-api-openapi.yml
  format: yaml
  label: Cloudovňa Invitations API
  slug: cloudovna-eu-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invitations-api-openapi.yml
- filename: cloudovna-eu-invoices-api-openapi.yml
  format: yaml
  label: Cloudovňa Invoices API
  slug: cloudovna-eu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-invoices-api-openapi.yml
- filename: cloudovna-eu-mcp-api-openapi.yml
  format: yaml
  label: Cloudovňa MCP API
  slug: cloudovna-eu-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-mcp-api-openapi.yml
- filename: cloudovna-eu-oauth-api-openapi.yml
  format: yaml
  label: Cloudovňa OAuth API
  slug: cloudovna-eu-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-oauth-api-openapi.yml
- filename: cloudovna-eu-organizations-api-openapi.yml
  format: yaml
  label: Cloudovňa Organizations API
  slug: cloudovna-eu-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-organizations-api-openapi.yml
- filename: cloudovna-eu-payments-api-openapi.yml
  format: yaml
  label: Cloudovňa Payments API
  slug: cloudovna-eu-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-payments-api-openapi.yml
- filename: cloudovna-eu-pool-api-openapi.yml
  format: yaml
  label: Cloudovňa Pool API
  slug: cloudovna-eu-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-pool-api-openapi.yml
- filename: cloudovna-eu-public-api-openapi.yml
  format: yaml
  label: Cloudovňa Public API
  slug: cloudovna-eu-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-public-api-openapi.yml
- filename: cloudovna-eu-services-api-openapi.yml
  format: yaml
  label: Cloudovňa Services API
  slug: cloudovna-eu-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-services-api-openapi.yml
- filename: cloudovna-eu-stacks-api-openapi.yml
  format: yaml
  label: Cloudovňa Stacks API
  slug: cloudovna-eu-stacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-stacks-api-openapi.yml
- filename: cloudovna-eu-well-known-api-openapi.yml
  format: yaml
  label: Cloudovňa .well Known API
  slug: cloudovna-eu-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudovna-eu/openapi/cloudovna-eu-well-known-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Servers in the EU
  entity_types:
  - text: If you are a consumer, you may withdraw from a distance contract within 14 days of it being formed without giving a reason
    type: individual
  - text: Managed hosting, server rental and consulting for businesses are agreed individually.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or rights-infringing content
    text: or for content that breaks the law or infringes the rights of others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A new account with a verified email can try its first resource pool of up to 1 vCPU, 1 GB of memory, 5 GB of disk and 1 GB of database space free for 7 days, once.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cloudovňa
provenance_date: '2026-11-09'
provider_name: Cloudovňa
provider_slug: cloudovna-eu
slug: cloudovna-eu-eligibility
source_date: '2026-11-09'
source_filename: cloudovna-eu-eligibility.yml
source_heading: Eligibility
source_page: https://cloudovna.eu/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloudovňa\naid: cloudovna-eu\nurl: https://cloudovna.eu/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Servers in the EU\nentity_types:\n- type: individual\n  text: If you are a consumer, you may withdraw from a distance contract within 14 days of it being formed without\n    giving a reason\n- type: business\n  text: Managed hosting, server rental and consulting for businesses are agreed individually.\nrestricted_uses:\n- summary: Unlawful or rights-infringing content\n  text: or for content that breaks the law or infringes the rights of others.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: A new account with a verified email can try its first resource pool of up to 1 vCPU, 1 GB of memory, 5 GB\n    of disk and 1 GB of database space free for 7 days, once.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloudovna-eu/eligibility/cloudovna-eu-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Cloudovňa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Hosting
- Containers
- Docker
- Databases
- PostgreSQL
- SQL Server
- European Union
- MCP
---
