---
api_specs:
- filename: qwilt-certificate-templates-api-openapi.yml
  format: yaml
  label: Qwilt Certificate Templates API
  slug: qwilt-certificate-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-certificate-templates-api-openapi.yml
- filename: qwilt-certificates-api-openapi.yml
  format: yaml
  label: Qwilt Certificates API
  slug: qwilt-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-certificates-api-openapi.yml
- filename: qwilt-origin-allow-list-api-openapi.yml
  format: yaml
  label: Qwilt Origin Allow List API
  slug: qwilt-origin-allow-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-origin-allow-list-api-openapi.yml
- filename: qwilt-publishing-operations-api-openapi.yml
  format: yaml
  label: Qwilt Publishing Operations API
  slug: qwilt-publishing-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-publishing-operations-api-openapi.yml
- filename: qwilt-site-configurations-api-openapi.yml
  format: yaml
  label: Qwilt Site Configurations API
  slug: qwilt-site-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-site-configurations-api-openapi.yml
- filename: qwilt-sites-api-openapi.yml
  format: yaml
  label: Qwilt Sites API
  slug: qwilt-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qwilt/openapi/qwilt-sites-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged thirteen (13) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: solely for your own personal and non-commercial use
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
name: Qwilt
provenance_date: '2026-11-10'
provider_name: Qwilt
provider_slug: qwilt
slug: qwilt-eligibility
source_date: '2026-11-10'
source_filename: qwilt-eligibility.yml
source_heading: Eligibility
source_page: https://qwilt.com/qwilt-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qwilt\naid: qwilt\nurl: https://qwilt.com/qwilt-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: solely for your own personal and non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/qwilt/eligibility/qwilt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Qwilt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- CDN
- Edge Computing
- Video Streaming
- Open Caching
- Media Delivery
- Certificates
- Infrastructure
---
