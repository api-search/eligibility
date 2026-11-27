---
api_specs:
- filename: upapi-io-communication-api-openapi.yml
  format: yaml
  label: upapi-io Communication API
  slug: upapi-io-communication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-communication-api-openapi.yml
- filename: upapi-io-data-api-openapi.yml
  format: yaml
  label: upapi-io Data API
  slug: upapi-io-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-data-api-openapi.yml
- filename: upapi-io-developer-tools-api-openapi.yml
  format: yaml
  label: upapi-io Developer Tools API
  slug: upapi-io-developer-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-developer-tools-api-openapi.yml
- filename: upapi-io-finance-api-openapi.yml
  format: yaml
  label: upapi-io Finance API
  slug: upapi-io-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-finance-api-openapi.yml
- filename: upapi-io-maps-api-openapi.yml
  format: yaml
  label: upapi-io Maps API
  slug: upapi-io-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-maps-api-openapi.yml
- filename: upapi-io-media-api-openapi.yml
  format: yaml
  label: upapi-io Media API
  slug: upapi-io-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-media-api-openapi.yml
- filename: upapi-io-search-api-openapi.yml
  format: yaml
  label: upapi-io Search API
  slug: upapi-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-search-api-openapi.yml
- filename: upapi-io-seo-tools-api-openapi.yml
  format: yaml
  label: upapi-io SEO tools API
  slug: upapi-io-seo-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-seo-tools-api-openapi.yml
- filename: upapi-io-social-media-api-openapi.yml
  format: yaml
  label: upapi-io Social Media API
  slug: upapi-io-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-social-media-api-openapi.yml
- filename: upapi-io-tools-api-openapi.yml
  format: yaml
  label: upapi-io Tools API
  slug: upapi-io-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-tools-api-openapi.yml
- filename: upapi-io-utility-api-openapi.yml
  format: yaml
  label: upapi-io Utility API
  slug: upapi-io-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-utility-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind it
    type: business
  minimum_age:
    text: You must be at least 16 years old, or the age of digital consent where you live, to use the Services.
    value: '16'
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: break the law, infringe anyone's rights, or help someone else do so
  - summary: Connected accounts of others
    text: Do not connect an account that belongs to someone else unless they have authorized you to.
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
name: upapi-io
provenance_date: '2026-11-10'
provider_name: upapi-io
provider_slug: upapi-io
slug: upapi-io-eligibility
source_date: '2026-11-10'
source_filename: upapi-io-eligibility.yml
source_heading: Eligibility
source_page: https://upapi.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: upapi-io\naid: upapi-io\nurl: https://upapi.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind it\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: break the law, infringe anyone's rights, or help someone else do so\n- summary: Connected accounts of others\n  text: Do not connect an account that belongs to someone else unless they have authorized you to.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or the age of digital consent where you live, to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/upapi-io/eligibility/upapi-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from upapi-io's own page on 2026-11-10.
synthetic: false
tags:
- API Marketplace
- Developer Tools
- Data
- Automation
- Integration
---
