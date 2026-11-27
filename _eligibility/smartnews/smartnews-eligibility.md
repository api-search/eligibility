---
api_specs:
- filename: smartnews-ad-api-openapi.yml
  format: yaml
  label: SmartNews Ad API
  slug: smartnews-ad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-ad-api-openapi.yml
- filename: smartnews-ad-group-api-openapi.yml
  format: yaml
  label: SmartNews Ad Group API
  slug: smartnews-ad-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-ad-group-api-openapi.yml
- filename: smartnews-article-category-api-openapi.yml
  format: yaml
  label: SmartNews article category API
  slug: smartnews-article-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-article-category-api-openapi.yml
- filename: smartnews-campaign-api-openapi.yml
  format: yaml
  label: SmartNews Campaign API
  slug: smartnews-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-campaign-api-openapi.yml
- filename: smartnews-catalog-api-openapi.yml
  format: yaml
  label: SmartNews Catalog API
  slug: smartnews-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-catalog-api-openapi.yml
- filename: smartnews-channel-alias-label-api-openapi.yml
  format: yaml
  label: SmartNews channel alias label API
  slug: smartnews-channel-alias-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-channel-alias-label-api-openapi.yml
- filename: smartnews-custom-audience-api-openapi.yml
  format: yaml
  label: SmartNews Custom Audience API
  slug: smartnews-custom-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-custom-audience-api-openapi.yml
- filename: smartnews-developer-app-api-openapi.yml
  format: yaml
  label: SmartNews Developer App API
  slug: smartnews-developer-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-developer-app-api-openapi.yml
- filename: smartnews-insights-api-openapi.yml
  format: yaml
  label: SmartNews Insights API
  slug: smartnews-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-insights-api-openapi.yml
- filename: smartnews-interests-api-openapi.yml
  format: yaml
  label: SmartNews Interests API
  slug: smartnews-interests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-interests-api-openapi.yml
- filename: smartnews-locations-api-openapi.yml
  format: yaml
  label: SmartNews Locations API
  slug: smartnews-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-locations-api-openapi.yml
- filename: smartnews-media-file-api-openapi.yml
  format: yaml
  label: SmartNews Media File API
  slug: smartnews-media-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-media-file-api-openapi.yml
- filename: smartnews-pixel-api-openapi.yml
  format: yaml
  label: SmartNews Pixel API
  slug: smartnews-pixel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-pixel-api-openapi.yml
- filename: smartnews-smart-view-article-keyword-api-openapi.yml
  format: yaml
  label: SmartNews smart view article keyword API
  slug: smartnews-smart-view-article-keyword-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-smart-view-article-keyword-api-openapi.yml
- filename: smartnews-oauth-api-openapi.yml
  format: yaml
  label: SmartNews OAUTH API
  slug: smartnews-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smartnews/openapi/smartnews-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Persons who are, or who are in a country or region that is, sanctioned or embargoed by Japan, the U.S., or other relevant governmental authority may not access or use our API or Advertising Data.
  entity_types:
  - text: developers who develop API Clients (as defined below)
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive activity
    text: To engage in unlawful, fraudulent, or abusive activities.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to our API requires API keys or other credentials, which will be provided to Accessing Parties upon approval by us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SmartNews
provenance_date: '2026-11-10'
provider_name: SmartNews
provider_slug: smartnews
slug: smartnews-eligibility
source_date: '2026-11-10'
source_filename: smartnews-eligibility.yml
source_heading: Eligibility
source_page: https://ads.smartnews.com/developers/tos-en.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmartNews\naid: smartnews\nurl: https://ads.smartnews.com/developers/tos-en.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Persons who are, or who are in a country or region that is, sanctioned or embargoed by Japan, the U.S.,\n    or other relevant governmental authority may not access or use our API or Advertising Data.\nentity_types:\n- type: developer\n  text: developers who develop API Clients (as defined below)\nrestricted_uses:\n- summary: Unlawful or abusive activity\n  text: To engage in unlawful, fraudulent, or abusive activities.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: true\n  text: Access to our API requires API keys or other credentials, which will be provided to Accessing Parties upon\n    approval by us.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smartnews/eligibility/smartnews-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from SmartNews's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- News
- Advertising
- AdTech
- Marketing
- Media
- Campaign Management
---
