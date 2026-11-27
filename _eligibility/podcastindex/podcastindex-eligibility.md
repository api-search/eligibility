---
api_specs:
- filename: podcastindex-add-api-openapi.yml
  format: yaml
  label: PodcastIndex Add API
  slug: podcastindex-add-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-add-api-openapi.yml
- filename: podcastindex-apple-replacement-api-openapi.yml
  format: yaml
  label: PodcastIndex Apple Replacement API
  slug: podcastindex-apple-replacement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-apple-replacement-api-openapi.yml
- filename: podcastindex-categories-api-openapi.yml
  format: yaml
  label: PodcastIndex Categories API
  slug: podcastindex-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-categories-api-openapi.yml
- filename: podcastindex-episodes-api-openapi.yml
  format: yaml
  label: PodcastIndex Episodes API
  slug: podcastindex-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-episodes-api-openapi.yml
- filename: podcastindex-hub-api-openapi.yml
  format: yaml
  label: PodcastIndex Hub API
  slug: podcastindex-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-hub-api-openapi.yml
- filename: podcastindex-podcasts-api-openapi.yml
  format: yaml
  label: PodcastIndex Podcasts API
  slug: podcastindex-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-podcasts-api-openapi.yml
- filename: podcastindex-recent-api-openapi.yml
  format: yaml
  label: PodcastIndex Recent API
  slug: podcastindex-recent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-recent-api-openapi.yml
- filename: podcastindex-search-api-openapi.yml
  format: yaml
  label: PodcastIndex Search API
  slug: podcastindex-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-search-api-openapi.yml
- filename: podcastindex-static-data-api-openapi.yml
  format: yaml
  label: PodcastIndex Static Data API
  slug: podcastindex-static-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-static-data-api-openapi.yml
- filename: podcastindex-stats-api-openapi.yml
  format: yaml
  label: PodcastIndex Stats API
  slug: podcastindex-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-stats-api-openapi.yml
- filename: podcastindex-value-api-openapi.yml
  format: yaml
  label: PodcastIndex Value API
  slug: podcastindex-value-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podcastindex/openapi/podcastindex-value-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Podcast Index
    type: individual
  minimum_age:
    text: you are not of legal age to form a binding contract with Podcast Index
    value: null
  restricted_uses:
  - summary: Life-critical uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: Unlawful gambling or disruptive ads
    text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.
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
name: PodcastIndex
provenance_date: '2026-11-10'
provider_name: PodcastIndex
provider_slug: podcastindex
slug: podcastindex-eligibility
source_date: '2026-11-10'
source_filename: podcastindex-eligibility.yml
source_heading: Eligibility
source_page: https://github.com/Podcastindex-org/legal/blob/main/TermsOfService.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PodcastIndex\naid: podcastindex\nurl: https://github.com/Podcastindex-org/legal/blob/main/TermsOfService.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs and may not accept the Terms if ... you are a person barred from using or receiving\n    the APIs under the applicable laws of the United States or other countries including the country in which you\n    are resident or from which you use the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that\
  \ entity to the Terms\n- type: individual\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Podcast Index\nrestricted_uses:\n- summary: Life-critical uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: Unlawful gambling or disruptive ads\n  text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with Podcast Index\n"
source_yaml_url: https://artifacts.apis.io/podcastindex/eligibility/podcastindex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from PodcastIndex's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Podcast Index
- Discovery
- Open Data
---
