---
api_specs:
- filename: dyno-nobel-robotslandingpage-api-openapi.yml
  format: yaml
  label: Dyno Nobel Robots Landing Page API
  slug: dyno-nobel-robotslandingpage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dyno-nobel/openapi/dyno-nobel-robotslandingpage-api-openapi.yml
- filename: dyno-nobel-robotstext-api-openapi.yml
  format: yaml
  label: Dyno Nobel Robots Text API
  slug: dyno-nobel-robotstext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dyno-nobel/openapi/dyno-nobel-robotstext-api-openapi.yml
- filename: dyno-nobel-searchapi-api-openapi.yml
  format: yaml
  label: Dyno Nobel Search API
  slug: dyno-nobel-searchapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dyno-nobel/openapi/dyno-nobel-searchapi-api-openapi.yml
- filename: dyno-nobel-sitemanifest-api-openapi.yml
  format: yaml
  label: Dyno Nobel Site Manifest API
  slug: dyno-nobel-sitemanifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dyno-nobel/openapi/dyno-nobel-sitemanifest-api-openapi.yml
claim_count: 1
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
  - summary: Explosives compliance
    text: Buyer covenants and agrees to transport, use, and store the Products only in strict compliance with those laws and regulations.
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
name: Dyno Nobel
provenance_date: '2026-11-09'
provider_name: Dyno Nobel
provider_slug: dyno-nobel
slug: dyno-nobel-eligibility
source_date: '2026-11-09'
source_filename: dyno-nobel-eligibility.yml
source_heading: Eligibility
source_page: https://www.dynonobel.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dyno Nobel\naid: dyno-nobel\nurl: https://www.dynonobel.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Explosives compliance\n  text: Buyer covenants and agrees to transport, use, and store the Products only in strict compliance with those\n    laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dyno-nobel/eligibility/dyno-nobel-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Dyno Nobel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Explosives
- Mining
- Industrial Manufacturing
- Blasting
- Australia
---
