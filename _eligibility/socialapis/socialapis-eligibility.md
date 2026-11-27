---
api_specs:
- filename: socialapis-account-api-openapi.yml
  format: yaml
  label: SocialAPIs Account API
  slug: socialapis-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-account-api-openapi.yml
- filename: socialapis-facebook-groups-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Groups API
  slug: socialapis-facebook-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-groups-api-openapi.yml
- filename: socialapis-facebook-marketplace-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Marketplace API
  slug: socialapis-facebook-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-marketplace-api-openapi.yml
- filename: socialapis-facebook-media-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Media API
  slug: socialapis-facebook-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-media-api-openapi.yml
- filename: socialapis-facebook-pages-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Pages API
  slug: socialapis-facebook-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-pages-api-openapi.yml
- filename: socialapis-facebook-posts-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Posts API
  slug: socialapis-facebook-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-posts-api-openapi.yml
- filename: socialapis-facebook-search-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Search API
  slug: socialapis-facebook-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-search-api-openapi.yml
- filename: socialapis-instagram-api-openapi.yml
  format: yaml
  label: SocialAPIs Instagram API
  slug: socialapis-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-instagram-api-openapi.yml
- filename: socialapis-meta-ads-library-api-openapi.yml
  format: yaml
  label: SocialAPIs Meta Ads Library API
  slug: socialapis-meta-ads-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-meta-ads-library-api-openapi.yml
- filename: socialapis-other-api-openapi.yml
  format: yaml
  label: SocialAPIs Other API
  slug: socialapis-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-other-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Service, you represent that you are at least 18 years old and have the legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: No tracking or profiling individuals
    text: Track, profile, or surveil individuals, or build databases of private persons
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
name: SocialAPIs
provenance_date: '2026-11-10'
provider_name: SocialAPIs
provider_slug: socialapis
slug: socialapis-eligibility
source_date: '2026-11-10'
source_filename: socialapis-eligibility.yml
source_heading: Eligibility
source_page: https://socialapis.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SocialAPIs\naid: socialapis\nurl: https://socialapis.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No tracking or profiling individuals\n  text: Track, profile, or surveil individuals, or build databases of private persons\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Service, you represent that you are at least 18 years old and have the legal capacity to enter\n    into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/socialapis/eligibility/socialapis-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from SocialAPIs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Data
- Developers
---
