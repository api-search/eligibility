---
api_specs:
- filename: podcast-co-episodes-api-openapi.yml
  format: yaml
  label: Podcast.co Episodes API
  slug: podcast-co-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcast-co/openapi/podcast-co-episodes-api-openapi.yml
- filename: podcast-co-podcast-page-api-openapi.yml
  format: yaml
  label: Podcast.co podcast page API
  slug: podcast-co-podcast-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcast-co/openapi/podcast-co-podcast-page-api-openapi.yml
- filename: podcast-co-podcasts-api-openapi.yml
  format: yaml
  label: Podcast.co Podcasts API
  slug: podcast-co-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcast-co/openapi/podcast-co-podcasts-api-openapi.yml
- filename: podcast-co-subscribe-button-api-openapi.yml
  format: yaml
  label: Podcast.co subscribe button API
  slug: podcast-co-subscribe-button-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcast-co/openapi/podcast-co-subscribe-button-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
    type: business
  - text: If you are using the Services for a personal purpose, then nothing in these terms or any additional terms limits any consumers’ legal rights which may not be waived by contract.
    type: individual
  minimum_age:
    text: Our Services are very diverse, so sometimes additional terms or product requirements (including age requirements) may apply.
    value: null
  restricted_uses:
  - summary: Discriminatory content
    text: 'content that directly discriminates others (including but not limited to: racism, sexism, sexual orientation discrimination) is not permitted on the platform.'
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
name: Podcast.co
provenance_date: '2026-11-10'
provider_name: Podcast.co
provider_slug: podcast-co
slug: podcast-co-eligibility
source_date: '2026-11-10'
source_filename: podcast-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.podcast.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Podcast.co\naid: podcast-co\nurl: https://www.podcast.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\n- type: individual\n  text: If you are using the Services for a personal purpose, then nothing in these terms or any additional terms\n    limits any consumers’ legal rights which may not be waived by contract.\nrestricted_uses:\n- summary: Discriminatory content\n  text: 'content that directly discriminates others (including but not limited\
  \ to: racism, sexism, sexual orientation\n    discrimination) is not permitted on the platform.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Our Services are very diverse, so sometimes additional terms or product requirements (including age requirements)\n    may apply.\n"
source_yaml_url: https://artifacts.apis.io/podcast-co/eligibility/podcast-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Podcast.co's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Hosting
- Audio
- Software-as-a-Service
- Media
---
