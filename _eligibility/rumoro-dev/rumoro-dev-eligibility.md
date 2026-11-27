---
api_specs:
- filename: rumoro-dev-alerts-api-openapi.yml
  format: yaml
  label: rumoro-dev Alerts API
  slug: rumoro-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-alerts-api-openapi.yml
- filename: rumoro-dev-analytics-api-openapi.yml
  format: yaml
  label: rumoro-dev Analytics API
  slug: rumoro-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-analytics-api-openapi.yml
- filename: rumoro-dev-api-keys-api-openapi.yml
  format: yaml
  label: rumoro-dev API keys API
  slug: rumoro-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-api-keys-api-openapi.yml
- filename: rumoro-dev-attention-api-openapi.yml
  format: yaml
  label: rumoro-dev Attention API
  slug: rumoro-dev-attention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-attention-api-openapi.yml
- filename: rumoro-dev-auth-api-openapi.yml
  format: yaml
  label: rumoro-dev Auth API
  slug: rumoro-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-auth-api-openapi.yml
- filename: rumoro-dev-billing-api-openapi.yml
  format: yaml
  label: rumoro-dev Billing API
  slug: rumoro-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-billing-api-openapi.yml
- filename: rumoro-dev-company-api-openapi.yml
  format: yaml
  label: rumoro-dev Company API
  slug: rumoro-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-company-api-openapi.yml
- filename: rumoro-dev-filters-api-openapi.yml
  format: yaml
  label: rumoro-dev Filters API
  slug: rumoro-dev-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-filters-api-openapi.yml
- filename: rumoro-dev-groups-api-openapi.yml
  format: yaml
  label: rumoro-dev Groups API
  slug: rumoro-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-groups-api-openapi.yml
- filename: rumoro-dev-keywords-api-openapi.yml
  format: yaml
  label: rumoro-dev Keywords API
  slug: rumoro-dev-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-keywords-api-openapi.yml
- filename: rumoro-dev-members-api-openapi.yml
  format: yaml
  label: rumoro-dev Members API
  slug: rumoro-dev-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-members-api-openapi.yml
- filename: rumoro-dev-mentions-api-openapi.yml
  format: yaml
  label: rumoro-dev Mentions API
  slug: rumoro-dev-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-mentions-api-openapi.yml
- filename: rumoro-dev-people-api-openapi.yml
  format: yaml
  label: rumoro-dev People API
  slug: rumoro-dev-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-people-api-openapi.yml
- filename: rumoro-dev-segments-api-openapi.yml
  format: yaml
  label: rumoro-dev Segments API
  slug: rumoro-dev-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-segments-api-openapi.yml
- filename: rumoro-dev-system-api-openapi.yml
  format: yaml
  label: rumoro-dev System API
  slug: rumoro-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-system-api-openapi.yml
- filename: rumoro-dev-usage-api-openapi.yml
  format: yaml
  label: rumoro-dev Usage API
  slug: rumoro-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-usage-api-openapi.yml
- filename: rumoro-dev-views-api-openapi.yml
  format: yaml
  label: rumoro-dev Views API
  slug: rumoro-dev-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rumoro-dev/openapi/rumoro-dev-views-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: only sign up if you can enter into a binding contract
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No profiling or targeting by sensitive traits
    text: to profile individual people or target them by sensitive traits such as health, politics or religion
  - summary: No surveillance or law enforcement use of Reddit content
    text: or for surveillance or law enforcement
  - summary: No background checks
    text: to run background checks
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
name: rumoro-dev
provenance_date: '2026-11-10'
provider_name: rumoro-dev
provider_slug: rumoro-dev
slug: rumoro-dev-eligibility
source_date: '2026-11-10'
source_filename: rumoro-dev-eligibility.yml
source_heading: Eligibility
source_page: https://rumoro.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rumoro-dev\naid: rumoro-dev\nurl: https://rumoro.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: only sign up if you can enter into a binding contract\nrestricted_uses:\n- summary: No profiling or targeting by sensitive traits\n  text: to profile individual people or target them by sensitive traits such as health, politics or religion\n- summary: No surveillance or law enforcement use of Reddit content\n  text: or for surveillance or law enforcement\n- summary: No background checks\n  text: to run background checks\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rumoro-dev/eligibility/rumoro-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from rumoro-dev's own page on 2026-11-10.
synthetic: false
tags:
- Social Listening
- Artificial Intelligence
- Monitoring
- Analytics
---
