---
api_specs:
- filename: imgur-account-api-openapi.yml
  format: yaml
  label: Imgur Account API
  slug: imgur-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-account-api-openapi.yml
- filename: imgur-album-api-openapi.yml
  format: yaml
  label: Imgur Album API
  slug: imgur-album-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-album-api-openapi.yml
- filename: imgur-auth-api-openapi.yml
  format: yaml
  label: Imgur Auth API
  slug: imgur-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-auth-api-openapi.yml
- filename: imgur-comment-api-openapi.yml
  format: yaml
  label: Imgur Comment API
  slug: imgur-comment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-comment-api-openapi.yml
- filename: imgur-gallery-api-openapi.yml
  format: yaml
  label: Imgur Gallery API
  slug: imgur-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-gallery-api-openapi.yml
- filename: imgur-image-api-openapi.yml
  format: yaml
  label: Imgur Image API
  slug: imgur-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-image-api-openapi.yml
- filename: imgur-memegen-api-openapi.yml
  format: yaml
  label: Imgur Memegen API
  slug: imgur-memegen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-memegen-api-openapi.yml
- filename: imgur-notification-api-openapi.yml
  format: yaml
  label: Imgur Notification API
  slug: imgur-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-notification-api-openapi.yml
- filename: imgur-tags-api-openapi.yml
  format: yaml
  label: Imgur Tags API
  slug: imgur-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-tags-api-openapi.yml
- filename: imgur-topic-api-openapi.yml
  format: yaml
  label: Imgur Topic API
  slug: imgur-topic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imgur/openapi/imgur-topic-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our service (including, our App, Website, and UGC) is for your personal use and may not be used for direct commercial endeavors without the express written consent of us.
    type: business
  minimum_age:
    text: Imgur is not meant for use by children under age 13
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: may not be used for direct commercial endeavors without the express written consent of us
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
name: Imgur
provenance_date: '2026-11-09'
provider_name: Imgur
provider_slug: imgur
slug: imgur-eligibility
source_date: '2026-11-09'
source_filename: imgur-eligibility.yml
source_heading: Eligibility
source_page: https://imgur.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imgur\naid: imgur\nurl: https://imgur.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our service (including, our App, Website, and UGC) is for your personal use and may not be used for direct\n    commercial endeavors without the express written consent of us.\nrestricted_uses:\n- summary: Commercial use\n  text: may not be used for direct commercial endeavors without the express written consent of us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Imgur\
  \ is not meant for use by children under age 13\n"
source_yaml_url: https://artifacts.apis.io/imgur/eligibility/imgur-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Imgur's own page on 2026-11-09.
synthetic: false
tags:
- Photography
- Image
- Image Hosting
- Albums
- Gallery
- Social
- Memes
- Content Sharing
- Public APIs
---
