---
api_specs:
- filename: localytics-audiences-api-openapi.yml
  format: yaml
  label: Localytics Audiences API
  slug: localytics-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-audiences-api-openapi.yml
- filename: localytics-campaigns-api-openapi.yml
  format: yaml
  label: Localytics Campaigns API
  slug: localytics-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-campaigns-api-openapi.yml
- filename: localytics-push-campaigns-api-openapi.yml
  format: yaml
  label: Localytics Push Campaigns API
  slug: localytics-push-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-push-campaigns-api-openapi.yml
- filename: localytics-meta-api-openapi.yml
  format: yaml
  label: Localytics Meta API
  slug: localytics-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-meta-api-openapi.yml
- filename: localytics-push-api-openapi.yml
  format: yaml
  label: Localytics Push API
  slug: localytics-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-push-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not use the Services in restricted jurisdictions or for prohibited purposes.
  entity_types:
  - text: '"Customer" means the entity entering into an agreement with Localytics.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted jurisdictions and prohibited purposes
    text: Customer may not use the Services in restricted jurisdictions or for prohibited purposes.
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
name: Localytics
provenance_date: '2026-11-09'
provider_name: Localytics
provider_slug: localytics
slug: localytics-eligibility
source_date: '2026-11-09'
source_filename: localytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.localytics.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Localytics\naid: localytics\nurl: https://www.localytics.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not use the Services in restricted jurisdictions or for prohibited purposes.\nentity_types:\n- type: business\n  text: '\"Customer\" means the entity entering into an agreement with Localytics.'\nrestricted_uses:\n- summary: Restricted jurisdictions and prohibited purposes\n  text: Customer may not use the Services in restricted jurisdictions or for prohibited purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/localytics/eligibility/localytics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Localytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MarTech
- Mobile Analytics
- Push Notifications
- Customer Engagement
- Marketing Automation
- Mobile
- Segmentation
- Audiences
- Event Ingestion
- gRPC
---
