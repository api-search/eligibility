---
api_specs:
- filename: mparticle-data-plan-api-openapi.yml
  format: yaml
  label: mParticle Data Plan API
  slug: mparticle-data-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-data-plan-api-openapi.yml
- filename: mparticle-data-plan-version-api-openapi.yml
  format: yaml
  label: mParticle Data Plan Version API
  slug: mparticle-data-plan-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-data-plan-version-api-openapi.yml
- filename: mparticle-events-api-openapi.yml
  format: yaml
  label: mParticle Events API
  slug: mparticle-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-events-api-openapi.yml
- filename: mparticle-identify-api-openapi.yml
  format: yaml
  label: mParticle Identify API
  slug: mparticle-identify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-identify-api-openapi.yml
- filename: mparticle-login-api-openapi.yml
  format: yaml
  label: mParticle Login API
  slug: mparticle-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-login-api-openapi.yml
- filename: mparticle-logout-api-openapi.yml
  format: yaml
  label: mParticle Logout API
  slug: mparticle-logout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-logout-api-openapi.yml
- filename: mparticle-modify-api-openapi.yml
  format: yaml
  label: mParticle Modify API
  slug: mparticle-modify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mparticle/openapi/mparticle-modify-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not, and will not allow any Authorized User to, remove or export from the United States ... into (or to a national or resident of) any embargoed or terrorist-supporting country
  entity_types:
  - text: solely for Customer’s internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data
    text: Customer will not use the mParticle Platform to collect, transmit, provide, or otherwise make available “sensitive information”, “sensitive data” or “special categories of personal data”
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
name: mParticle
provenance_date: '2026-11-10'
provider_name: mParticle
provider_slug: mparticle
slug: mparticle-eligibility
source_date: '2026-11-10'
source_filename: mparticle-eligibility.yml
source_heading: Eligibility
source_page: https://www.rokt.com/policies/mparticle-platform-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mParticle\naid: mparticle\nurl: https://www.rokt.com/policies/mparticle-platform-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not, and will not allow any Authorized User to, remove or export from the United States ...\n    into (or to a national or resident of) any embargoed or terrorist-supporting country\nentity_types:\n- type: business\n  text: solely for Customer’s internal business purposes\nrestricted_uses:\n- summary: Sensitive data\n  text: Customer will not use the mParticle Platform to collect, transmit, provide, or otherwise\
  \ make available\n    “sensitive information”, “sensitive data” or “special categories of personal data”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mparticle/eligibility/mparticle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from mParticle's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Analytics
- Identity Resolution
- Audiences
- Data Pipeline
- Marketing Data
- Event Streaming
- Data Governance
---
