---
api_specs:
- filename: zdnet-ai-api-openapi.yml
  format: yaml
  label: ZDNet AI API
  slug: zdnet-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zdnet/openapi/zdnet-ai-api-openapi.yml
- filename: zdnet-cloud-api-openapi.yml
  format: yaml
  label: ZDNet Cloud API
  slug: zdnet-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zdnet/openapi/zdnet-cloud-api-openapi.yml
- filename: zdnet-news-api-openapi.yml
  format: yaml
  label: ZDNet News API
  slug: zdnet-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zdnet/openapi/zdnet-news-api-openapi.yml
- filename: zdnet-security-api-openapi.yml
  format: yaml
  label: ZDNet Security API
  slug: zdnet-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zdnet/openapi/zdnet-security-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users of the Services may use the Content only for their personal, noncommercial use.
    type: individual
  - text: Businesses, organizations or other legal entities may not become Members
    type: business
  minimum_age:
    text: You must be 13 years of age or older to use the Services outside of the European Union and European Economic Area, and 16 years of age or older in the European Union and European Economic Area.
    value: '13'
  restricted_uses:
  - summary: Commercial use of Content
    text: Users of the Services may use the Content only for their personal, noncommercial use.
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
name: ZDNet
provenance_date: '2026-11-10'
provider_name: ZDNet
provider_slug: zdnet
slug: zdnet-eligibility
source_date: '2026-11-10'
source_filename: zdnet-eligibility.yml
source_heading: Eligibility
source_page: https://www.ziffdavis.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZDNet\naid: zdnet\nurl: https://www.ziffdavis.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users of the Services may use the Content only for their personal, noncommercial use.\n- type: business\n  text: Businesses, organizations or other legal entities may not become Members\nrestricted_uses:\n- summary: Commercial use of Content\n  text: Users of the Services may use the Content only for their personal, noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older to use the Services outside of the European Union and European Economic\n    Area, and 16 years of age or older in the European Union and European Economic Area.\n"
source_yaml_url: https://artifacts.apis.io/zdnet/eligibility/zdnet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ZDNet's own page on 2026-11-10.
synthetic: false
tags:
- Enterprise IT
- Media
- Technology News
---
