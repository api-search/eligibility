---
api_specs:
- filename: tenor-autocomplete-api-openapi.yml
  format: yaml
  label: Tenor Autocomplete API
  slug: tenor-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-autocomplete-api-openapi.yml
- filename: tenor-categories-api-openapi.yml
  format: yaml
  label: Tenor Categories API
  slug: tenor-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-categories-api-openapi.yml
- filename: tenor-featured-api-openapi.yml
  format: yaml
  label: Tenor Featured API
  slug: tenor-featured-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-featured-api-openapi.yml
- filename: tenor-posts-api-openapi.yml
  format: yaml
  label: Tenor Posts API
  slug: tenor-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-posts-api-openapi.yml
- filename: tenor-registershare-api-openapi.yml
  format: yaml
  label: Tenor Registershare API
  slug: tenor-registershare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-registershare-api-openapi.yml
- filename: tenor-search-api-openapi.yml
  format: yaml
  label: Tenor Search API
  slug: tenor-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-search-api-openapi.yml
- filename: tenor-search-suggestions-api-openapi.yml
  format: yaml
  label: Tenor Search Suggestions API
  slug: tenor-search-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-search-suggestions-api-openapi.yml
- filename: tenor-trending-terms-api-openapi.yml
  format: yaml
  label: Tenor Trending Terms API
  slug: tenor-trending-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenor/openapi/tenor-trending-terms-api-openapi.yml
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
  - summary: Commercial or third-party use barred
    text: You must not use Tenor for any commercial purpose or for the benefit of any third party.
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
name: Tenor
provenance_date: '2026-11-10'
provider_name: Tenor
provider_slug: tenor
slug: tenor-eligibility
source_date: '2026-11-10'
source_filename: tenor-eligibility.yml
source_heading: Eligibility
source_page: https://tenor.com/legal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tenor\naid: tenor\nurl: https://tenor.com/legal-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial or third-party use barred\n  text: You must not use Tenor for any commercial purpose or for the benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tenor/eligibility/tenor-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Tenor's own page on 2026-11-10.
synthetic: false
tags:
- GIFs
- Animated Images
- Search
- Media
- Google
---
