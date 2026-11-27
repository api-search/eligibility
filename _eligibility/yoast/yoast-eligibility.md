---
api_specs:
- filename: yoast-pages-api-openapi.yml
  format: yaml
  label: Yoast Pages API
  slug: yoast-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-pages-api-openapi.yml
- filename: yoast-posts-api-openapi.yml
  format: yaml
  label: Yoast Posts API
  slug: yoast-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-posts-api-openapi.yml
- filename: yoast-seo-head-api-openapi.yml
  format: yaml
  label: Yoast SEO Head API
  slug: yoast-seo-head-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-seo-head-api-openapi.yml
- filename: yoast-abilities-api-openapi.yml
  format: yaml
  label: Yoast SEO Abilities API
  slug: yoast-abilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-abilities-api-openapi.yml
- filename: yoast-provisioning-account-api-openapi.yml
  format: yaml
  label: Yoast Provisioning Account API
  slug: yoast-provisioning-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-provisioning-account-api-openapi.yml
- filename: yoast-provisioning-downloads-api-openapi.yml
  format: yaml
  label: Yoast Provisioning Downloads API
  slug: yoast-provisioning-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-provisioning-downloads-api-openapi.yml
- filename: yoast-provisioning-users-api-openapi.yml
  format: yaml
  label: Yoast Provisioning Users API
  slug: yoast-provisioning-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-provisioning-users-api-openapi.yml
- filename: yoast-schema-aggregator-api-openapi.yml
  format: yaml
  label: Yoast Schema Aggregator API
  slug: yoast-schema-aggregator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-schema-aggregator-api-openapi.yml
- filename: yoast-subscription-provisioning-api-openapi.yml
  format: yaml
  label: Yoast Subscription Provisioning API
  slug: yoast-subscription-provisioning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoast/openapi/yoast-subscription-provisioning-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: provide accurate, current and complete information about you and your organization (if applicable)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sharing personal data with Yoast
    text: You shall not share any personal data with Yoast other than described in our Privacy Notice.
  - summary: Sensitive data in AI Services
    text: You agree not to input any private sensitive information into the AI Services.
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
name: Yoast
provenance_date: '2026-11-10'
provider_name: Yoast
provider_slug: yoast
slug: yoast-eligibility
source_date: '2026-11-10'
source_filename: yoast-eligibility.yml
source_heading: Eligibility
source_page: https://yoast.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yoast\naid: yoast\nurl: https://yoast.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: provide accurate, current and complete information about you and your organization (if applicable)\nrestricted_uses:\n- summary: Sharing personal data with Yoast\n  text: You shall not share any personal data with Yoast other than described in our Privacy Notice.\n- summary: Sensitive data in AI Services\n  text: You agree not to input any private sensitive information into the AI Services.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yoast/eligibility/yoast-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Yoast's own page on 2026-11-10.
synthetic: false
tags:
- SEO
- WordPress
- Content Optimization
- Schema
- Metadata
- Structured Data
- Content Analysis
- Agent Readiness
- Plugins
---
