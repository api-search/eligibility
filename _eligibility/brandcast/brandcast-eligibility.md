---
api_specs:
- filename: brandcast-account-api-openapi.yml
  format: yaml
  label: Brandcast Account API
  slug: brandcast-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandcast/openapi/brandcast-account-api-openapi.yml
- filename: brandcast-salesforce-api-openapi.yml
  format: yaml
  label: Brandcast Salesforce API
  slug: brandcast-salesforce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandcast/openapi/brandcast-salesforce-api-openapi.yml
- filename: brandcast-templates-api-openapi.yml
  format: yaml
  label: Brandcast Templates API
  slug: brandcast-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandcast/openapi/brandcast-templates-api-openapi.yml
- filename: brandcast-websites-api-openapi.yml
  format: yaml
  label: Brandcast Websites API
  slug: brandcast-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brandcast/openapi/brandcast-websites-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Subscriber shall not permit access or use of any Services in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan, Syria, or Crimea) or in violation of any U.S. export law or regulation.
  entity_types:
  - text: Each Party is a business duly incorporated and in good standing under the laws of its state of incorporation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and denied-party restrictions
    text: Services may be subject to export laws and regulations of the United States and other jurisdictions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brandcast
provenance_date: '2026-11-09'
provider_name: Brandcast
provider_slug: brandcast
slug: brandcast-eligibility
source_date: '2026-11-09'
source_filename: brandcast-eligibility.yml
source_heading: Eligibility
source_page: https://www.sites.design/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brandcast\naid: brandcast\nurl: https://www.sites.design/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Subscriber shall not permit access or use of any Services in a U.S. embargoed country (currently Cuba, Iran,\n    North Korea, Sudan, Syria, or Crimea) or in violation of any U.S. export law or regulation.\nentity_types:\n- type: business\n  text: Each Party is a business duly incorporated and in good standing under the laws of its state of incorporation.\nrestricted_uses:\n- summary: Export and denied-party restrictions\n  text: Services\
  \ may be subject to export laws and regulations of the United States and other jurisdictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brandcast/eligibility/brandcast-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Brandcast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Software
- No-Code
- Website Builder
- Content Management
- Digital Experience
- Web Design
- Brand Management
---
