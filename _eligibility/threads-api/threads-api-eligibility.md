---
api_specs:
- filename: threads-api-authorization-api-openapi.yml
  format: yaml
  label: Threads Authorization API
  slug: threads-api-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-authorization-api-openapi.yml
- filename: threads-api-post-to-threads-quote-threads-posts-api-openapi.yml
  format: yaml
  label: Threads Post to Threads > Quote Threads Posts API
  slug: threads-api-post-to-threads-quote-threads-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-post-to-threads-quote-threads-posts-api-openapi.yml
- filename: threads-api-post-to-threads-repost-threads-posts-api-openapi.yml
  format: yaml
  label: Threads Post to Threads > Repost Threads Posts API
  slug: threads-api-post-to-threads-repost-threads-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-post-to-threads-repost-threads-posts-api-openapi.yml
- filename: threads-api-read-and-manage-threads-read-and-manage-threads-replies-api-openapi.yml
  format: yaml
  label: Threads Read And Manage Threads > Read and Manage Threads Replies API
  slug: threads-api-read-and-manage-threads-read-and-manage-threads-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-read-and-manage-threads-read-and-manage-threads-replies-api-openapi.yml
- filename: threads-api-read-and-manage-threads-read-replies-media-objects-api-openapi.yml
  format: yaml
  label: Threads Read And Manage Threads > Read Replies Media Objects API
  slug: threads-api-read-and-manage-threads-read-replies-media-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-read-and-manage-threads-read-replies-media-objects-api-openapi.yml
- filename: threads-api-read-and-manage-threads-read-threads-insights-api-openapi.yml
  format: yaml
  label: Threads Read And Manage Threads > Read Threads Insights API
  slug: threads-api-read-and-manage-threads-read-threads-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-read-and-manage-threads-read-threads-insights-api-openapi.yml
- filename: threads-api-read-and-manage-threads-retrieve-threads-media-objects-api-openapi.yml
  format: yaml
  label: Threads Read And Manage Threads > Retrieve Threads Media Objects API
  slug: threads-api-read-and-manage-threads-retrieve-threads-media-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-read-and-manage-threads-retrieve-threads-media-objects-api-openapi.yml
- filename: threads-api-read-and-manage-threads-retrieve-threads-profiles-api-openapi.yml
  format: yaml
  label: Threads Read And Manage Threads > Retrieve Threads Profiles API
  slug: threads-api-read-and-manage-threads-retrieve-threads-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-read-and-manage-threads-retrieve-threads-profiles-api-openapi.yml
- filename: threads-api-troubleshooting-api-openapi.yml
  format: yaml
  label: Threads Troubleshooting API
  slug: threads-api-troubleshooting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threads-api/openapi/threads-api-troubleshooting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Developer” means the person or entity that creates or operates an App.
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Eligibility determinations
    text: Processing Platform Data to make eligibility determinations about people, including for housing, employment, insurance, education opportunities, credit, government benefits, or immigration status.
  - summary: Discrimination
    text: Processing Platform Data to discriminate or encourage discrimination in a manner that disadvantages people based on personal attributes
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
name: Threads
provenance_date: '2026-11-10'
provider_name: Threads
provider_slug: threads-api
slug: threads-api-eligibility
source_date: '2026-11-10'
source_filename: threads-api-eligibility.yml
source_heading: Eligibility
source_page: https://developers.facebook.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Threads\naid: threads-api\nurl: https://developers.facebook.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: “Developer” means the person or entity that creates or operates an App.\nrestricted_uses:\n- summary: Eligibility determinations\n  text: Processing Platform Data to make eligibility determinations about people, including for housing, employment,\n    insurance, education opportunities, credit, government benefits, or immigration status.\n- summary: Discrimination\n  text: Processing Platform Data to discriminate or\
  \ encourage discrimination in a manner that disadvantages people\n    based on personal attributes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/threads-api/eligibility/threads-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Threads's own page on 2026-11-10.
synthetic: false
tags:
- Social
- Social Network
- Meta
- Publishing
- Media
---
