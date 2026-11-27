---
api_specs:
- filename: createmod-com-analytics-api-openapi.yml
  format: yaml
  label: CreateMod.com Analytics API
  slug: createmod-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-analytics-api-openapi.yml
- filename: createmod-com-mod-integration-api-openapi.yml
  format: yaml
  label: CreateMod.com Mod Integration API
  slug: createmod-com-mod-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-mod-integration-api-openapi.yml
- filename: createmod-com-schematics-api-openapi.yml
  format: yaml
  label: CreateMod.com Schematics API
  slug: createmod-com-schematics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-schematics-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Payments may be unavailable in some countries and regions where Stripe does not offer its services.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purpose
    text: You agree not to use the Site for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be a registered user to post or upload content.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CreateMod.com
provenance_date: '2026-11-09'
provider_name: CreateMod.com
provider_slug: createmod-com
slug: createmod-com-eligibility
source_date: '2026-11-09'
source_filename: createmod-com-eligibility.yml
source_heading: Eligibility
source_page: https://createmod.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CreateMod.com\naid: createmod-com\nurl: https://createmod.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Payments may be unavailable in some countries and regions where Stripe does not offer its services.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purpose\n  text: You agree not to use the Site for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a registered user to post or upload content.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/createmod-com/eligibility/createmod-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from CreateMod.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Minecraft
- Gaming
- Schematics
- Create Mod
- Community
- User Generated Content
- REST API
---
