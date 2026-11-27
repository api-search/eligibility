---
api_specs:
- filename: clearlist-me-account-api-openapi.yml
  format: yaml
  label: ClearList Account API
  slug: clearlist-me-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-account-api-openapi.yml
- filename: clearlist-me-jobs-api-openapi.yml
  format: yaml
  label: ClearList Jobs API
  slug: clearlist-me-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-jobs-api-openapi.yml
- filename: clearlist-me-listings-api-openapi.yml
  format: yaml
  label: ClearList Listings API
  slug: clearlist-me-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-listings-api-openapi.yml
- filename: clearlist-me-onboarding-api-openapi.yml
  format: yaml
  label: ClearList Onboarding API
  slug: clearlist-me-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-onboarding-api-openapi.yml
- filename: clearlist-me-orders-api-openapi.yml
  format: yaml
  label: ClearList Orders API
  slug: clearlist-me-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-orders-api-openapi.yml
- filename: clearlist-me-publishing-api-openapi.yml
  format: yaml
  label: ClearList Publishing API
  slug: clearlist-me-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-publishing-api-openapi.yml
- filename: clearlist-me-scheduling-api-openapi.yml
  format: yaml
  label: ClearList Scheduling API
  slug: clearlist-me-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-scheduling-api-openapi.yml
- filename: clearlist-me-system-api-openapi.yml
  format: yaml
  label: ClearList System API
  slug: clearlist-me-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-system-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited item categories
    text: 'Prohibited items include: firearms, weapons, adult content, live animals, drugs, and hazardous materials.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create a seller account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClearList
provenance_date: '2026-11-09'
provider_name: ClearList
provider_slug: clearlist-me
slug: clearlist-me-eligibility
source_date: '2026-11-09'
source_filename: clearlist-me-eligibility.yml
source_heading: Eligibility
source_page: https://clearlist.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearList\naid: clearlist-me\nurl: https://clearlist.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited item categories\n  text: 'Prohibited items include: firearms, weapons, adult content, live animals, drugs, and hazardous materials.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create a seller account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearlist-me/eligibility/clearlist-me-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from ClearList's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Resale
- Marketplace
- Automation
- E-Commerce
- Company
---
