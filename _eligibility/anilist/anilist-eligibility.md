---
api_specs:
- filename: anilist-oauth2-api-openapi.yml
  format: yaml
  label: AniList O Auth2 API
  slug: anilist-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-oauth2-api-openapi.yml
- filename: anilist-graph-ql-api-openapi.yml
  format: yaml
  label: AniList Graph QL API
  slug: anilist-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anilist/openapi/anilist-graph-ql-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Applications or services operating at greating than $150 of revenue per month will need to acquire a commercial license.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing services
    text: Use of the AniList API within competing, non-complementary services of the same nature is prohibited. This includes, but is not limited to, anime and manga list or tracker services.
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
name: AniList
provenance_date: '2026-11-09'
provider_name: AniList
provider_slug: anilist
slug: anilist-eligibility
source_date: '2026-11-09'
source_filename: anilist-eligibility.yml
source_heading: Eligibility
source_page: https://docs.anilist.co/guide/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AniList\naid: anilist\nurl: https://docs.anilist.co/guide/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Applications or services operating at greating than $150 of revenue per month will need to acquire a commercial\n    license.\nrestricted_uses:\n- summary: Competing services\n  text: Use of the AniList API within competing, non-complementary services of the same nature is prohibited. This\n    includes, but is not limited to, anime and manga list or tracker services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anilist/eligibility/anilist-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AniList's own page on 2026-11-09.
synthetic: false
tags:
- Anime
- Manga
- Entertainment
- Media
- Social
- Database
- GraphQL
- OAuth
- Public APIs
- Authentication
---
