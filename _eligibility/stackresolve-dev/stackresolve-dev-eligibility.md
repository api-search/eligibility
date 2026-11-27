---
api_specs:
- filename: stackresolve-dev-account-api-openapi.yml
  format: yaml
  label: stackresolve-dev Account API
  slug: stackresolve-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-account-api-openapi.yml
- filename: stackresolve-dev-audit-api-openapi.yml
  format: yaml
  label: stackresolve-dev Audit API
  slug: stackresolve-dev-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-audit-api-openapi.yml
- filename: stackresolve-dev-company-api-openapi.yml
  format: yaml
  label: stackresolve-dev Company API
  slug: stackresolve-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-company-api-openapi.yml
- filename: stackresolve-dev-compare-api-openapi.yml
  format: yaml
  label: stackresolve-dev Compare API
  slug: stackresolve-dev-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-compare-api-openapi.yml
- filename: stackresolve-dev-competitors-api-openapi.yml
  format: yaml
  label: stackresolve-dev Competitors API
  slug: stackresolve-dev-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-competitors-api-openapi.yml
- filename: stackresolve-dev-find-tools-api-openapi.yml
  format: yaml
  label: stackresolve-dev Find Tools API
  slug: stackresolve-dev-find-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-find-tools-api-openapi.yml
- filename: stackresolve-dev-plans-api-openapi.yml
  format: yaml
  label: stackresolve-dev Plans API
  slug: stackresolve-dev-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-plans-api-openapi.yml
- filename: stackresolve-dev-pricing-api-openapi.yml
  format: yaml
  label: stackresolve-dev Pricing API
  slug: stackresolve-dev-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-pricing-api-openapi.yml
- filename: stackresolve-dev-profile-api-openapi.yml
  format: yaml
  label: stackresolve-dev Profile API
  slug: stackresolve-dev-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-profile-api-openapi.yml
- filename: stackresolve-dev-registry-api-openapi.yml
  format: yaml
  label: stackresolve-dev Registry API
  slug: stackresolve-dev-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-registry-api-openapi.yml
- filename: stackresolve-dev-research-api-openapi.yml
  format: yaml
  label: stackresolve-dev Research API
  slug: stackresolve-dev-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-research-api-openapi.yml
- filename: stackresolve-dev-search-api-openapi.yml
  format: yaml
  label: stackresolve-dev Search API
  slug: stackresolve-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackresolve-dev/openapi/stackresolve-dev-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you use the Service for an organization, you promise that you are authorized to accept these Terms for that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose or in violation of any applicable law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You can register with an email and password, or sign in with GitHub or Google through our authentication provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: stackresolve-dev
provenance_date: '2026-11-10'
provider_name: stackresolve-dev
provider_slug: stackresolve-dev
slug: stackresolve-dev-eligibility
source_date: '2026-11-10'
source_filename: stackresolve-dev-eligibility.yml
source_heading: Eligibility
source_page: https://stackresolve.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: stackresolve-dev\naid: stackresolve-dev\nurl: https://stackresolve.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you use the Service for an organization, you promise that you are authorized to accept these Terms for\n    that organization\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose or in violation of any applicable law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You can register with an email and password, or sign in with GitHub or Google through our authentication\n    provider.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/stackresolve-dev/eligibility/stackresolve-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from stackresolve-dev's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- Software Registry
- Web Intelligence
- API Platform
- Developer Tools
---
