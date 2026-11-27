---
api_specs:
- filename: restosignals-com-account-api-openapi.yml
  format: yaml
  label: restosignals-com Account API
  slug: restosignals-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-account-api-openapi.yml
- filename: restosignals-com-auth-api-openapi.yml
  format: yaml
  label: restosignals-com Auth API
  slug: restosignals-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-auth-api-openapi.yml
- filename: restosignals-com-billing-api-openapi.yml
  format: yaml
  label: restosignals-com Billing API
  slug: restosignals-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-billing-api-openapi.yml
- filename: restosignals-com-config-api-openapi.yml
  format: yaml
  label: restosignals-com Config API
  slug: restosignals-com-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-config-api-openapi.yml
- filename: restosignals-com-export-api-openapi.yml
  format: yaml
  label: restosignals-com Export API
  slug: restosignals-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-export-api-openapi.yml
- filename: restosignals-com-health-api-openapi.yml
  format: yaml
  label: restosignals-com Health API
  slug: restosignals-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-health-api-openapi.yml
- filename: restosignals-com-keys-api-openapi.yml
  format: yaml
  label: restosignals-com Keys API
  slug: restosignals-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-keys-api-openapi.yml
- filename: restosignals-com-mcp-api-openapi.yml
  format: yaml
  label: restosignals-com MCP API
  slug: restosignals-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-mcp-api-openapi.yml
- filename: restosignals-com-me-api-openapi.yml
  format: yaml
  label: restosignals-com Me API
  slug: restosignals-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-me-api-openapi.yml
- filename: restosignals-com-openings-api-openapi.yml
  format: yaml
  label: restosignals-com Openings API
  slug: restosignals-com-openings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-openings-api-openapi.yml
- filename: restosignals-com-register-api-openapi.yml
  format: yaml
  label: restosignals-com Register API
  slug: restosignals-com-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-register-api-openapi.yml
- filename: restosignals-com-signals-api-openapi.yml
  format: yaml
  label: restosignals-com Signals API
  slug: restosignals-com-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-signals-api-openapi.yml
- filename: restosignals-com-usage-api-openapi.yml
  format: yaml
  label: restosignals-com Usage API
  slug: restosignals-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-usage-api-openapi.yml
- filename: restosignals-com-webhooks-api-openapi.yml
  format: yaml
  label: restosignals-com Webhooks API
  slug: restosignals-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful contact or marketing to venues
    text: You are responsible for complying with all laws that apply to how you contact or market to the venues you discover.
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
name: restosignals-com
provenance_date: '2026-11-10'
provider_name: restosignals-com
provider_slug: restosignals-com
slug: restosignals-com-eligibility
source_date: '2026-11-10'
source_filename: restosignals-com-eligibility.yml
source_heading: Eligibility
source_page: https://restosignals.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: restosignals-com\naid: restosignals-com\nurl: https://restosignals.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful contact or marketing to venues\n  text: You are responsible for complying with all laws that apply to how you contact or market to the venues you\n    discover.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/restosignals-com/eligibility/restosignals-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from restosignals-com's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Data
- MCP
- Lead Generation
---
