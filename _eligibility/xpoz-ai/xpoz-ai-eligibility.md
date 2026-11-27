---
api_specs:
- filename: xpoz-ai-account-api-openapi.yml
  format: yaml
  label: xpoz-ai Account API
  slug: xpoz-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-account-api-openapi.yml
- filename: xpoz-ai-billing-api-openapi.yml
  format: yaml
  label: xpoz-ai Billing API
  slug: xpoz-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-billing-api-openapi.yml
- filename: xpoz-ai-crawl-settings-api-openapi.yml
  format: yaml
  label: xpoz-ai Crawl Settings API
  slug: xpoz-ai-crawl-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-crawl-settings-api-openapi.yml
- filename: xpoz-ai-instagram-live-api-openapi.yml
  format: yaml
  label: xpoz-ai Instagram (live) API
  slug: xpoz-ai-instagram-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-instagram-live-api-openapi.yml
- filename: xpoz-ai-operations-api-openapi.yml
  format: yaml
  label: xpoz-ai Operations API
  slug: xpoz-ai-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-operations-api-openapi.yml
- filename: xpoz-ai-platform-api-openapi.yml
  format: yaml
  label: xpoz-ai Platform API
  slug: xpoz-ai-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-platform-api-openapi.yml
- filename: xpoz-ai-reddit-live-api-openapi.yml
  format: yaml
  label: xpoz-ai Reddit (live) API
  slug: xpoz-ai-reddit-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-reddit-live-api-openapi.yml
- filename: xpoz-ai-system-status-api-openapi.yml
  format: yaml
  label: xpoz-ai System Status API
  slug: xpoz-ai-system-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-system-status-api-openapi.yml
- filename: xpoz-ai-tiktok-live-api-openapi.yml
  format: yaml
  label: xpoz-ai TikTok (live) API
  slug: xpoz-ai-tiktok-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-tiktok-live-api-openapi.yml
- filename: xpoz-ai-twitter-live-api-openapi.yml
  format: yaml
  label: xpoz-ai Twitter (live) API
  slug: xpoz-ai-twitter-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xpoz-ai/openapi/xpoz-ai-twitter-live-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old, or you have full legal authority to enter into these Terms.
    type: individual
  - text: If you are using the Service on behalf of a company or organization, you are authorized to bind that entity.
    type: business
  minimum_age:
    text: You are at least 18 years old, or you have full legal authority to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Harassment or unlawful profiling
    text: Use the Service to harass, harm, target, or unlawfully profile individuals or organizations.
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
name: xpoz-ai
provenance_date: '2026-11-10'
provider_name: xpoz-ai
provider_slug: xpoz-ai
slug: xpoz-ai-eligibility
source_date: '2026-11-10'
source_filename: xpoz-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.xpoz.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: xpoz-ai\naid: xpoz-ai\nurl: https://www.xpoz.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old, or you have full legal authority to enter into these Terms.\n- type: business\n  text: If you are using the Service on behalf of a company or organization, you are authorized to bind that entity.\nrestricted_uses:\n- summary: Harassment or unlawful profiling\n  text: Use the Service to harass, harm, target, or unlawfully profile individuals or organizations.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old, or you have full legal authority to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/xpoz-ai/eligibility/xpoz-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from xpoz-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Data
- Artificial Intelligence
- Monitoring
- Analytics
- SDK
---
