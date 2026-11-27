---
api_specs:
- filename: facebook-ad-accounts-api-openapi.yml
  format: yaml
  label: Facebook Ad Accounts API
  slug: facebook-ad-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-ad-accounts-api-openapi.yml
- filename: facebook-ad-sets-api-openapi.yml
  format: yaml
  label: Facebook Ad Sets API
  slug: facebook-ad-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-ad-sets-api-openapi.yml
- filename: facebook-ads-api-openapi.yml
  format: yaml
  label: Facebook Ads API
  slug: facebook-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-ads-api-openapi.yml
- filename: facebook-audiences-api-openapi.yml
  format: yaml
  label: Facebook Audiences API
  slug: facebook-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-audiences-api-openapi.yml
- filename: facebook-authentication-api-openapi.yml
  format: yaml
  label: Facebook Authentication API
  slug: facebook-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-authentication-api-openapi.yml
- filename: facebook-campaigns-api-openapi.yml
  format: yaml
  label: Facebook Campaigns API
  slug: facebook-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-campaigns-api-openapi.yml
- filename: facebook-comments-api-openapi.yml
  format: yaml
  label: Facebook Comments API
  slug: facebook-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-comments-api-openapi.yml
- filename: facebook-conversations-api-openapi.yml
  format: yaml
  label: Facebook Conversations API
  slug: facebook-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-conversations-api-openapi.yml
- filename: facebook-insights-api-openapi.yml
  format: yaml
  label: Facebook Insights API
  slug: facebook-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-insights-api-openapi.yml
- filename: facebook-media-api-openapi.yml
  format: yaml
  label: Facebook Media API
  slug: facebook-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-media-api-openapi.yml
- filename: facebook-messages-api-openapi.yml
  format: yaml
  label: Facebook Messages API
  slug: facebook-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-messages-api-openapi.yml
- filename: facebook-pages-api-openapi.yml
  format: yaml
  label: Facebook Pages API
  slug: facebook-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-pages-api-openapi.yml
- filename: facebook-phone-numbers-api-openapi.yml
  format: yaml
  label: Facebook Phone Numbers API
  slug: facebook-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-phone-numbers-api-openapi.yml
- filename: facebook-photos-api-openapi.yml
  format: yaml
  label: Facebook Photos API
  slug: facebook-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-photos-api-openapi.yml
- filename: facebook-posts-api-openapi.yml
  format: yaml
  label: Facebook Posts API
  slug: facebook-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-posts-api-openapi.yml
- filename: facebook-profile-api-openapi.yml
  format: yaml
  label: Facebook Profile API
  slug: facebook-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-profile-api-openapi.yml
- filename: facebook-publishing-api-openapi.yml
  format: yaml
  label: Facebook Publishing API
  slug: facebook-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-publishing-api-openapi.yml
- filename: facebook-replies-api-openapi.yml
  format: yaml
  label: Facebook Replies API
  slug: facebook-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-replies-api-openapi.yml
- filename: facebook-tags-api-openapi.yml
  format: yaml
  label: Facebook Tags API
  slug: facebook-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-tags-api-openapi.yml
- filename: facebook-templates-api-openapi.yml
  format: yaml
  label: Facebook Templates API
  slug: facebook-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-templates-api-openapi.yml
- filename: facebook-users-api-openapi.yml
  format: yaml
  label: Facebook Users API
  slug: facebook-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facebook/openapi/facebook-users-api-openapi.yml
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
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may require that you submit your App for our review or approval
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Facebook
provenance_date: '2026-11-09'
provider_name: Facebook
provider_slug: facebook
slug: facebook-eligibility
source_date: '2026-11-09'
source_filename: facebook-eligibility.yml
source_heading: Eligibility
source_page: https://developers.facebook.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Facebook\naid: facebook\nurl: https://developers.facebook.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: “Developer” means the person or entity that creates or operates an App.\nrestricted_uses:\n- summary: Eligibility determinations\n  text: Processing Platform Data to make eligibility determinations about people, including for housing, employment,\n    insurance, education opportunities, credit, government benefits, or immigration status.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may\
  \ require that you submit your App for our review or approval\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/facebook/eligibility/facebook-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Facebook's own page on 2026-11-09.
synthetic: false
tags:
- Facebook
- Fortune 500
- Advertising
- Content Publishing
- Messaging
- Social Media
- Social Network
---
