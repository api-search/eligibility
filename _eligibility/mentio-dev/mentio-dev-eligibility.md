---
api_specs:
- filename: mentio-dev-alerts-api-openapi.yml
  format: yaml
  label: mentio-dev Alerts API
  slug: mentio-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-alerts-api-openapi.yml
- filename: mentio-dev-analytics-api-openapi.yml
  format: yaml
  label: mentio-dev Analytics API
  slug: mentio-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-analytics-api-openapi.yml
- filename: mentio-dev-api-keys-api-openapi.yml
  format: yaml
  label: mentio-dev API keys API
  slug: mentio-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-api-keys-api-openapi.yml
- filename: mentio-dev-attention-api-openapi.yml
  format: yaml
  label: mentio-dev Attention API
  slug: mentio-dev-attention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-attention-api-openapi.yml
- filename: mentio-dev-auth-api-openapi.yml
  format: yaml
  label: mentio-dev Auth API
  slug: mentio-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-auth-api-openapi.yml
- filename: mentio-dev-billing-api-openapi.yml
  format: yaml
  label: mentio-dev Billing API
  slug: mentio-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-billing-api-openapi.yml
- filename: mentio-dev-company-api-openapi.yml
  format: yaml
  label: mentio-dev Company API
  slug: mentio-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-company-api-openapi.yml
- filename: mentio-dev-feeds-api-openapi.yml
  format: yaml
  label: mentio-dev Feeds API
  slug: mentio-dev-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-feeds-api-openapi.yml
- filename: mentio-dev-filters-api-openapi.yml
  format: yaml
  label: mentio-dev Filters API
  slug: mentio-dev-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-filters-api-openapi.yml
- filename: mentio-dev-groups-api-openapi.yml
  format: yaml
  label: mentio-dev Groups API
  slug: mentio-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-groups-api-openapi.yml
- filename: mentio-dev-keywords-api-openapi.yml
  format: yaml
  label: mentio-dev Keywords API
  slug: mentio-dev-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-keywords-api-openapi.yml
- filename: mentio-dev-members-api-openapi.yml
  format: yaml
  label: mentio-dev Members API
  slug: mentio-dev-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-members-api-openapi.yml
- filename: mentio-dev-mentions-api-openapi.yml
  format: yaml
  label: mentio-dev Mentions API
  slug: mentio-dev-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-mentions-api-openapi.yml
- filename: mentio-dev-people-api-openapi.yml
  format: yaml
  label: mentio-dev People API
  slug: mentio-dev-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-people-api-openapi.yml
- filename: mentio-dev-segments-api-openapi.yml
  format: yaml
  label: mentio-dev Segments API
  slug: mentio-dev-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-segments-api-openapi.yml
- filename: mentio-dev-system-api-openapi.yml
  format: yaml
  label: mentio-dev System API
  slug: mentio-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-system-api-openapi.yml
- filename: mentio-dev-usage-api-openapi.yml
  format: yaml
  label: mentio-dev Usage API
  slug: mentio-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-usage-api-openapi.yml
- filename: mentio-dev-views-api-openapi.yml
  format: yaml
  label: mentio-dev Views API
  slug: mentio-dev-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-views-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be able to form a binding contract to use the service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Use the service only for lawful purposes.
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
name: mentio-dev
provenance_date: '2026-11-10'
provider_name: mentio-dev
provider_slug: mentio-dev
slug: mentio-dev-eligibility
source_date: '2026-11-10'
source_filename: mentio-dev-eligibility.yml
source_heading: Eligibility
source_page: https://mentio.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mentio-dev\naid: mentio-dev\nurl: https://mentio.dev/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be able to form a binding contract to use the service.\nrestricted_uses:\n- summary: Lawful use only\n  text: Use the service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mentio-dev/eligibility/mentio-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from mentio-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Listening
- AI Integration
- SDK
- Real-Time Monitoring
---
