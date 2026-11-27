---
api_specs:
- filename: bizverify-account-api-openapi.yml
  format: yaml
  label: BizVerify Account API
  slug: bizverify-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-account-api-openapi.yml
- filename: bizverify-auth-api-openapi.yml
  format: yaml
  label: BizVerify Auth API
  slug: bizverify-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-auth-api-openapi.yml
- filename: bizverify-billing-api-openapi.yml
  format: yaml
  label: BizVerify Billing API
  slug: bizverify-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-billing-api-openapi.yml
- filename: bizverify-entities-api-openapi.yml
  format: yaml
  label: BizVerify Entities API
  slug: bizverify-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-entities-api-openapi.yml
- filename: bizverify-meta-api-openapi.yml
  format: yaml
  label: BizVerify Meta API
  slug: bizverify-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-meta-api-openapi.yml
- filename: bizverify-public-api-openapi.yml
  format: yaml
  label: BizVerify Public API
  slug: bizverify-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-public-api-openapi.yml
- filename: bizverify-search-api-openapi.yml
  format: yaml
  label: BizVerify Search API
  slug: bizverify-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-search-api-openapi.yml
- filename: bizverify-tools-api-openapi.yml
  format: yaml
  label: BizVerify Tools API
  slug: bizverify-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-tools-api-openapi.yml
- filename: bizverify-verification-api-openapi.yml
  format: yaml
  label: BizVerify Verification API
  slug: bizverify-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-verification-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Building competing verification service
    text: No building a competing business verification service using our API
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
name: BizVerify
provenance_date: '2026-11-09'
provider_name: BizVerify
provider_slug: bizverify
slug: bizverify-eligibility
source_date: '2026-11-09'
source_filename: bizverify-eligibility.yml
source_heading: Eligibility
source_page: https://bizverify.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BizVerify\naid: bizverify\nurl: https://bizverify.co/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Building competing verification service\n  text: No building a competing business verification service using our API\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizverify/eligibility/bizverify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BizVerify's own page on 2026-11-09.
synthetic: false
tags:
- Business Verification
- KYB
- Entity Verification
- Compliance
- MCP
- Agent-Native
- Developer Tools
---
