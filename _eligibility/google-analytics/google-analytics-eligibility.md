---
api_specs:
- filename: google-analytics-accounts-api-openapi.yml
  format: yaml
  label: Google Analytics Accounts API
  slug: google-analytics-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-accounts-api-openapi.yml
- filename: google-analytics-accountsummaries-api-openapi.yml
  format: yaml
  label: Google Analytics Account Summaries API
  slug: google-analytics-accountsummaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-accountsummaries-api-openapi.yml
- filename: google-analytics-properties-api-openapi.yml
  format: yaml
  label: Google Analytics Properties API
  slug: google-analytics-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-analytics/openapi/google-analytics-properties-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CN
    - CU
    - IR
    - MM
    - KP
    - SD
    - SY
    served: []
    text: “Territory” means worldwide excluding China, Crimea, Cuba, Iran, Myanmar, North Korea, Sudan, Syria and any other country falling under U.S. export control regulations.
  entity_types:
  - text: the entity accepting this Agreement (“ Company ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only for Provisioning API
    text: Company may only use the Provisioning API for internal use cases
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- CU
- IR
- MM
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Analytics
provenance_date: '2026-11-09'
provider_name: Google Analytics
provider_slug: google-analytics
slug: google-analytics-eligibility
source_date: '2026-11-09'
source_filename: google-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/analytics/terms/provisioning/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Analytics\naid: google-analytics\nurl: https://developers.google.com/analytics/terms/provisioning/en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CN\n  - CU\n  - IR\n  - MM\n  - KP\n  - SD\n  - SY\n  text: “Territory” means worldwide excluding China, Crimea, Cuba, Iran, Myanmar, North Korea, Sudan, Syria and\n    any other country falling under U.S. export control regulations.\nentity_types:\n- type: business\n  text: the entity accepting this Agreement (“ Company ”)\nrestricted_uses:\n- summary: Internal use only for Provisioning API\n  text: Company may only use the Provisioning\
  \ API for internal use cases\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-analytics/eligibility/google-analytics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Data
- Google
- Metrics
- Reporting
- Web Analytics
- Machine Learning
- Attribution
---
