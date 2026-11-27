---
api_specs:
- filename: vice-media-oembed-1-0-api-openapi.yml
  format: yaml
  label: Vice Media Oembed/1.0 API
  slug: vice-media-oembed-1-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vice-media/openapi/vice-media-oembed-1-0-api-openapi.yml
- filename: vice-media-root-api-openapi.yml
  format: yaml
  label: Vice Media Root API
  slug: vice-media-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vice-media/openapi/vice-media-root-api-openapi.yml
- filename: vice-media-wp-abilities-v1-api-openapi.yml
  format: yaml
  label: Vice Media Wp Abilities/v1 API
  slug: vice-media-wp-abilities-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vice-media/openapi/vice-media-wp-abilities-v1-api-openapi.yml
- filename: vice-media-wp-v2-api-openapi.yml
  format: yaml
  label: Vice Media Wp/v2 API
  slug: vice-media-wp-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vice-media/openapi/vice-media-wp-v2-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served: []
    text: Software from any Site may not be downloaded, exported or re-exported into (or to a national or resident of) Cuba, North Korea, Iran, Syria or any other country to which the United States has embargoed goods
  entity_types:
  - text: If you are a minor, your parent or legal guardian has approved your participation on this Site and has read and agreed to these Terms on your behalf
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: You may not use the Sites for any purpose or in any manner that infringes the rights of any third party.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vice Media
provenance_date: '2026-11-10'
provider_name: Vice Media
provider_slug: vice-media
slug: vice-media-eligibility
source_date: '2026-11-10'
source_filename: vice-media-eligibility.yml
source_heading: Eligibility
source_page: https://www.vice.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vice Media\naid: vice-media\nurl: https://www.vice.com/en/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: Software from any Site may not be downloaded, exported or re-exported into (or to a national or resident\n    of) Cuba, North Korea, Iran, Syria or any other country to which the United States has embargoed goods\nentity_types:\n- type: individual\n  text: If you are a minor, your parent or legal guardian has approved your participation on this Site and has read\n    and agreed to these Terms on your behalf\nrestricted_uses:\n- summary: Unlawful\
  \ or infringing use\n  text: You may not use the Sites for any purpose or in any manner that infringes the rights of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vice-media/eligibility/vice-media-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Vice Media's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Publishing
- News
- Digital Media
- Content
- Video
- Entertainment
- WordPress
- Syndication
- oEmbed
- Brooklyn
---
