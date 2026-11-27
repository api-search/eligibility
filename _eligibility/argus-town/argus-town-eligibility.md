---
api_specs:
- filename: argus-town-alerts-api-openapi.yml
  format: yaml
  label: argus-town Alerts API
  slug: argus-town-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-alerts-api-openapi.yml
- filename: argus-town-connect-links-api-openapi.yml
  format: yaml
  label: argus-town Connect links API
  slug: argus-town-connect-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-connect-links-api-openapi.yml
- filename: argus-town-connections-api-openapi.yml
  format: yaml
  label: argus-town Connections API
  slug: argus-town-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-connections-api-openapi.yml
- filename: argus-town-events-api-openapi.yml
  format: yaml
  label: argus-town Events API
  slug: argus-town-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-events-api-openapi.yml
- filename: argus-town-negotiated-pricing-api-openapi.yml
  format: yaml
  label: argus-town Negotiated pricing API
  slug: argus-town-negotiated-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-negotiated-pricing-api-openapi.yml
- filename: argus-town-project-api-openapi.yml
  format: yaml
  label: argus-town Project API
  slug: argus-town-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-project-api-openapi.yml
- filename: argus-town-providers-api-openapi.yml
  format: yaml
  label: argus-town Providers API
  slug: argus-town-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-providers-api-openapi.yml
- filename: argus-town-spend-api-openapi.yml
  format: yaml
  label: argus-town Spend API
  slug: argus-town-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-spend-api-openapi.yml
- filename: argus-town-start-api-openapi.yml
  format: yaml
  label: argus-town Start API
  slug: argus-town-start-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-start-api-openapi.yml
- filename: argus-town-syncs-api-openapi.yml
  format: yaml
  label: argus-town Syncs API
  slug: argus-town-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-syncs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Argus on behalf of a company, you agree for that company and confirm you have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 18 and give a valid email address.
    value: '18'
  restricted_uses:
  - summary: Unauthorized credential use
    text: Connect credentials you aren't authorized to use, or use Argus to access accounts that aren't yours.
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
name: argus-town
provenance_date: '2026-11-09'
provider_name: argus-town
provider_slug: argus-town
slug: argus-town-eligibility
source_date: '2026-11-09'
source_filename: argus-town-eligibility.yml
source_heading: Eligibility
source_page: https://argus.town/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: argus-town\naid: argus-town\nurl: https://argus.town/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Argus on behalf of a company, you agree for that company and confirm you have authority to do\n    so.\nrestricted_uses:\n- summary: Unauthorized credential use\n  text: Connect credentials you aren't authorized to use, or use Argus to access accounts that aren't yours.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and give\
  \ a valid email address.\n"
source_yaml_url: https://artifacts.apis.io/argus-town/eligibility/argus-town-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from argus-town's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Monitoring
- Cost Management
- Developer Tools
- MCP
---
