---
api_specs:
- filename: appstorespy-app-store-api-openapi.yml
  format: yaml
  label: AppstoreSpy App Store API
  slug: appstorespy-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-app-store-api-openapi.yml
- filename: appstorespy-events-api-openapi.yml
  format: yaml
  label: AppstoreSpy Events API
  slug: appstorespy-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-events-api-openapi.yml
- filename: appstorespy-google-play-api-openapi.yml
  format: yaml
  label: AppstoreSpy Google Play API
  slug: appstorespy-google-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-google-play-api-openapi.yml
- filename: appstorespy-jobs-api-openapi.yml
  format: yaml
  label: AppstoreSpy Jobs API
  slug: appstorespy-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-jobs-api-openapi.yml
- filename: appstorespy-search-filter-v-2-api-openapi.yml
  format: yaml
  label: AppstoreSpy Search Filter v.2 API
  slug: appstorespy-search-filter-v-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-search-filter-v-2-api-openapi.yml
- filename: appstorespy-suggestions-api-openapi.yml
  format: yaml
  label: AppstoreSpy Suggestions API
  slug: appstorespy-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appstorespy/openapi/appstorespy-suggestions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of or a national or resident of any such restricted country.
  entity_types:
  - text: access and use the SaaS Services solely for its internal business operations
    type: business
  minimum_age:
    text: If you are below eighteen (18) years of age (or the age of majority where you live) you should decline to use Appstorespy Software and the Site.
    value: '18'
  restricted_uses:
  - summary: No illegal use or location masking
    text: You will not use any services for hiding or changing your real location in order to use or get access to the Software, for any illegal purposes, or in order to avoid restrictions provided by the government.
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
name: AppstoreSpy
provenance_date: '2026-11-09'
provider_name: AppstoreSpy
provider_slug: appstorespy
slug: appstorespy-eligibility
source_date: '2026-11-09'
source_filename: appstorespy-eligibility.yml
source_heading: Eligibility
source_page: https://appstorespy.com/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppstoreSpy\naid: appstorespy\nurl: https://appstorespy.com/agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of or a national or resident of\n    any such restricted country.\nentity_types:\n- type: business\n  text: access and use the SaaS Services solely for its internal business operations\nrestricted_uses:\n- summary: No illegal use or location masking\n  text: You will not use any services for hiding or changing your real location in order to use or get access to\n    the Software, for any illegal\
  \ purposes, or in order to avoid restrictions provided by the government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are below eighteen (18) years of age (or the age of majority where you live) you should decline to\n    use Appstorespy Software and the Site.\n"
source_yaml_url: https://artifacts.apis.io/appstorespy/eligibility/appstorespy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AppstoreSpy's own page on 2026-11-09.
synthetic: false
tags:
- Mobile App
- App Store Optimization
- Market Intelligence
- App Analytics
- Google Play
- apple-app-store
- Reviews and Ratings
- download-revenue-estimates
- Marketing
---
