---
api_specs:
- filename: prismareviews-connections-api-openapi.yml
  format: yaml
  label: Prisma Reviews Connections API
  slug: prismareviews-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-connections-api-openapi.yml
- filename: prismareviews-locations-api-openapi.yml
  format: yaml
  label: Prisma Reviews Locations API
  slug: prismareviews-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-locations-api-openapi.yml
- filename: prismareviews-platforms-api-openapi.yml
  format: yaml
  label: Prisma Reviews Platforms API
  slug: prismareviews-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-platforms-api-openapi.yml
- filename: prismareviews-replies-api-openapi.yml
  format: yaml
  label: Prisma Reviews Replies API
  slug: prismareviews-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-replies-api-openapi.yml
- filename: prismareviews-reviews-api-openapi.yml
  format: yaml
  label: Prisma Reviews Reviews API
  slug: prismareviews-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-reviews-api-openapi.yml
- filename: prismareviews-stats-api-openapi.yml
  format: yaml
  label: Prisma Reviews Stats API
  slug: prismareviews-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-stats-api-openapi.yml
- filename: prismareviews-usage-api-openapi.yml
  format: yaml
  label: Prisma Reviews Usage API
  slug: prismareviews-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-usage-api-openapi.yml
- filename: prismareviews-webhooks-api-openapi.yml
  format: yaml
  label: Prisma Reviews Webhooks API
  slug: prismareviews-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Prisma is a business service for companies and professionals. It is not offered to consumers, and you must be at least 18 to use it.
    type: business
  minimum_age:
    text: you must be at least 18 to use it.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: 'You must not use Prisma to: post fake, misleading, defamatory, discriminatory, harassing or unlawful replies'
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
name: Prisma Reviews
provenance_date: '2026-11-10'
provider_name: Prisma Reviews
provider_slug: prismareviews
slug: prismareviews-eligibility
source_date: '2026-11-10'
source_filename: prismareviews-eligibility.yml
source_heading: Eligibility
source_page: https://prismareviews.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prisma Reviews\naid: prismareviews\nurl: https://prismareviews.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Prisma is a business service for companies and professionals. It is not offered to consumers, and you must\n    be at least 18 to use it.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: 'You must not use Prisma to: post fake, misleading, defamatory, discriminatory, harassing or unlawful replies'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: you must be at least 18 to use it.\n"
source_yaml_url: https://artifacts.apis.io/prismareviews/eligibility/prismareviews-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Prisma Reviews's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Reviews
- Software-as-a-Service
- GDPR
- Spain
---
