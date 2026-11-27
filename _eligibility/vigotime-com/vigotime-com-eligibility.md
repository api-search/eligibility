---
api_specs:
- filename: vigotime-com-account-api-openapi.yml
  format: yaml
  label: vigotime-com Account API
  slug: vigotime-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-account-api-openapi.yml
- filename: vigotime-com-api-tokens-api-openapi.yml
  format: yaml
  label: vigotime-com API Tokens API
  slug: vigotime-com-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-api-tokens-api-openapi.yml
- filename: vigotime-com-health-api-openapi.yml
  format: yaml
  label: vigotime-com Health API
  slug: vigotime-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-health-api-openapi.yml
- filename: vigotime-com-signup-api-openapi.yml
  format: yaml
  label: vigotime-com Signup API
  slug: vigotime-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-signup-api-openapi.yml
- filename: vigotime-com-stateless-solve-api-openapi.yml
  format: yaml
  label: vigotime-com Stateless Solve API
  slug: vigotime-com-stateless-solve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-stateless-solve-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Der Dienst richtet sich ausschließlich an Unternehmer im Sinne von § 14 BGB (B2B).
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Der Kunde bestätigt, dass er berechtigt ist, im Namen der Organisation zu handeln und Verträge abzuschließen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: vigotime-com
provenance_date: '2026-11-10'
provider_name: vigotime-com
provider_slug: vigotime-com
slug: vigotime-com-eligibility
source_date: '2026-11-10'
source_filename: vigotime-com-eligibility.yml
source_heading: Eligibility
source_page: https://vigotime.com/de/terms-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vigotime-com\naid: vigotime-com\nurl: https://vigotime.com/de/terms-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Der Dienst richtet sich ausschließlich an Unternehmer im Sinne von § 14 BGB (B2B).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Der Kunde bestätigt, dass er berechtigt ist, im Namen der Organisation zu handeln und Verträge abzuschließen.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vigotime-com/eligibility/vigotime-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from vigotime-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Time Tracking
- Workforce Management
- Automation
---
