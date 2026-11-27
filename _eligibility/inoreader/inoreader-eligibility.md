---
api_specs:
- filename: inoreader-accounts-api-openapi.yml
  format: yaml
  label: Inoreader Accounts API
  slug: inoreader-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-accounts-api-openapi.yml
- filename: inoreader-oauth2-api-openapi.yml
  format: yaml
  label: Inoreader Oauth2 API
  slug: inoreader-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-oauth2-api-openapi.yml
- filename: inoreader-reader-api-openapi.yml
  format: yaml
  label: Inoreader Reader API
  slug: inoreader-reader-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-reader-api-openapi.yml
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
  - summary: Abusive use of platform
    text: we reserve the rights to block access or completely remove user accounts if we find out that the service is used in abusive manner.
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
name: Inoreader
provenance_date: '2026-11-09'
provider_name: Inoreader
provider_slug: inoreader
slug: inoreader-eligibility
source_date: '2026-11-09'
source_filename: inoreader-eligibility.yml
source_heading: Eligibility
source_page: https://www.inoreader.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inoreader\naid: inoreader\nurl: https://www.inoreader.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Abusive use of platform\n  text: we reserve the rights to block access or completely remove user accounts if we find out that the service\n    is used in abusive manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inoreader/eligibility/inoreader-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Inoreader's own page on 2026-11-09.
synthetic: false
tags:
- Company
- RSS
- Content Aggregation
- Productivity
---
