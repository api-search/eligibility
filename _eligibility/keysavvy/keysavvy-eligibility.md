---
api_specs:
- filename: keysavvy-authentication-api-openapi.yml
  format: yaml
  label: KeySavvy Authentication API
  slug: keysavvy-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-authentication-api-openapi.yml
- filename: keysavvy-deal-documents-api-openapi.yml
  format: yaml
  label: KeySavvy Deal Documents API
  slug: keysavvy-deal-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-deal-documents-api-openapi.yml
- filename: keysavvy-deal-management-api-openapi.yml
  format: yaml
  label: KeySavvy Deal Management API
  slug: keysavvy-deal-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-deal-management-api-openapi.yml
- filename: keysavvy-documents-api-openapi.yml
  format: yaml
  label: KeySavvy Documents API
  slug: keysavvy-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-documents-api-openapi.yml
- filename: keysavvy-keysavvy-partner-api-api-openapi.yml
  format: yaml
  label: KeySavvy KeySavvy Partner API
  slug: keysavvy-keysavvy-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-keysavvy-partner-api-api-openapi.yml
- filename: keysavvy-marketplace-management-api-openapi.yml
  format: yaml
  label: KeySavvy Marketplace Management API
  slug: keysavvy-marketplace-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-marketplace-management-api-openapi.yml
- filename: keysavvy-organization-management-api-openapi.yml
  format: yaml
  label: KeySavvy Organization Management API
  slug: keysavvy-organization-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-organization-management-api-openapi.yml
- filename: keysavvy-reporting-api-openapi.yml
  format: yaml
  label: KeySavvy Reporting API
  slug: keysavvy-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-reporting-api-openapi.yml
- filename: keysavvy-user-management-api-openapi.yml
  format: yaml
  label: KeySavvy User Management API
  slug: keysavvy-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-user-management-api-openapi.yml
- filename: keysavvy-vehicle-management-api-openapi.yml
  format: yaml
  label: KeySavvy Vehicle Management API
  slug: keysavvy-vehicle-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-vehicle-management-api-openapi.yml
- filename: keysavvy-webhook-management-api-openapi.yml
  format: yaml
  label: KeySavvy Webhook Management API
  slug: keysavvy-webhook-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keysavvy/openapi/keysavvy-webhook-management-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use.
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
name: KeySavvy
provenance_date: '2026-11-09'
provider_name: KeySavvy
provider_slug: keysavvy
slug: keysavvy-eligibility
source_date: '2026-11-09'
source_filename: keysavvy-eligibility.yml
source_heading: Eligibility
source_page: https://www.keysavvy.com:443/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KeySavvy\naid: keysavvy\nurl: https://www.keysavvy.com:443/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.\n"
source_yaml_url: https://artifacts.apis.io/keysavvy/eligibility/keysavvy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from KeySavvy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Marketplace
- Fintech
---
