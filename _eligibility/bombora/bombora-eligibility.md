---
api_specs:
- filename: bombora-intent-api-openapi.yml
  format: yaml
  label: Bombora Intent API
  slug: bombora-intent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-intent-api-openapi.yml
- filename: bombora-accounts-api-openapi.yml
  format: yaml
  label: Bombora Accounts API
  slug: bombora-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-accounts-api-openapi.yml
- filename: bombora-activate-api-openapi.yml
  format: yaml
  label: Bombora Activate API
  slug: bombora-activate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-activate-api-openapi.yml
- filename: bombora-data-api-openapi.yml
  format: yaml
  label: Bombora Data API
  slug: bombora-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-data-api-openapi.yml
- filename: bombora-demographic-api-openapi.yml
  format: yaml
  label: Bombora Demographic API
  slug: bombora-demographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-demographic-api-openapi.yml
- filename: bombora-destinations-api-openapi.yml
  format: yaml
  label: Bombora Destinations API
  slug: bombora-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-destinations-api-openapi.yml
- filename: bombora-digital-audience-builder-dab-api-api-openapi.yml
  format: yaml
  label: Bombora Digital Audience Builder (DAB) API
  slug: bombora-digital-audience-builder-dab-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-digital-audience-builder-dab-api-api-openapi.yml
- filename: bombora-estimate-api-openapi.yml
  format: yaml
  label: Bombora Estimate API
  slug: bombora-estimate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-estimate-api-openapi.yml
- filename: bombora-events-api-openapi.yml
  format: yaml
  label: Bombora Events API
  slug: bombora-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-events-api-openapi.yml
- filename: bombora-firmographic-api-openapi.yml
  format: yaml
  label: Bombora Firmographic API
  slug: bombora-firmographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-firmographic-api-openapi.yml
- filename: bombora-geographic-api-openapi.yml
  format: yaml
  label: Bombora Geographic API
  slug: bombora-geographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-geographic-api-openapi.yml
- filename: bombora-install-data-api-openapi.yml
  format: yaml
  label: Bombora Install Data API
  slug: bombora-install-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-install-data-api-openapi.yml
- filename: bombora-signaldefinition-api-openapi.yml
  format: yaml
  label: Bombora Signal Definition API
  slug: bombora-signaldefinition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-signaldefinition-api-openapi.yml
- filename: bombora-suspend-api-openapi.yml
  format: yaml
  label: Bombora Suspend API
  slug: bombora-suspend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-suspend-api-openapi.yml
- filename: bombora-oauth-api-openapi.yml
  format: yaml
  label: Bombora OAUTH API
  slug: bombora-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-oauth-api-openapi.yml
- filename: bombora-account-lists-api-openapi.yml
  format: yaml
  label: Bombora account lists API
  slug: bombora-account-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bombora/openapi/bombora-account-lists-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: Your account is personal to you and/or your organization
    type: business
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
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
name: Bombora
provenance_date: '2026-11-09'
provider_name: Bombora
provider_slug: bombora
slug: bombora-eligibility
source_date: '2026-11-09'
source_filename: bombora-eligibility.yml
source_heading: Eligibility
source_page: https://bombora.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bombora\naid: bombora\nurl: https://bombora.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: business\n  text: Your account is personal to you and/or your organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/bombora/eligibility/bombora-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bombora's own page on 2026-11-09.
synthetic: false
tags:
- Intent Data
- B2B Intent
- Company Surge
- Account Based Marketing
- Sales Intelligence
- Marketing Intelligence
- Identity Resolution
- Audience Activation
- Data Cooperative
- Webhook
- Reference Data
- AdTech
- MarTech
- B2B
- Account Lists
- Digital Audience Builder
- OpenAPI
---
