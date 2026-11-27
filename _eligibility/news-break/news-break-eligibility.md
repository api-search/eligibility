---
api_specs:
- filename: news-break-account-billing-api-openapi.yml
  format: yaml
  label: News Break Account Billing API
  slug: news-break-account-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-account-billing-api-openapi.yml
- filename: news-break-ad-account-api-openapi.yml
  format: yaml
  label: News Break Ad Account API
  slug: news-break-ad-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-ad-account-api-openapi.yml
- filename: news-break-ad-api-openapi.yml
  format: yaml
  label: News Break Ad API
  slug: news-break-ad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-ad-api-openapi.yml
- filename: news-break-ad-set-api-openapi.yml
  format: yaml
  label: News Break Ad Set API
  slug: news-break-ad-set-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-ad-set-api-openapi.yml
- filename: news-break-campaign-api-openapi.yml
  format: yaml
  label: News Break Campaign API
  slug: news-break-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-campaign-api-openapi.yml
- filename: news-break-event-management-api-openapi.yml
  format: yaml
  label: News Break Event Management API
  slug: news-break-event-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-event-management-api-openapi.yml
- filename: news-break-organization-api-openapi.yml
  format: yaml
  label: News Break Organization API
  slug: news-break-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-organization-api-openapi.yml
- filename: news-break-report-api-openapi.yml
  format: yaml
  label: News Break Report API
  slug: news-break-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-report-api-openapi.yml
- filename: news-break-reporting-api-openapi.yml
  format: yaml
  label: News Break Reporting API
  slug: news-break-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/news-break/openapi/news-break-reporting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Services you must be, and represent and warrant that you are, of legal age
    type: individual
  minimum_age:
    text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age)
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: only for your own internal, personal, or non-commercial use
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
name: News Break
provenance_date: '2026-11-10'
provider_name: News Break
provider_slug: news-break
slug: news-break-eligibility
source_date: '2026-11-10'
source_filename: news-break-eligibility.yml
source_heading: Eligibility
source_page: https://www.newsbreak.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: News Break\naid: news-break\nurl: https://www.newsbreak.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Services you must be, and represent and warrant that you are, of legal age\nrestricted_uses:\n- summary: Non-commercial use only\n  text: only for your own internal, personal, or non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if\
  \ you have parental\n    consent, 13 years of age)\n"
source_yaml_url: https://artifacts.apis.io/news-break/eligibility/news-break-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from News Break's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- News
- Media
- Local News
- Publishing
- Monetization
- Campaign Management
- Reporting
- Analytics
- Content
---
