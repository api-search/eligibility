---
api_specs:
- filename: astraverify-com-discoverability-api-openapi.yml
  format: yaml
  label: AstraVerify Discoverability API
  slug: astraverify-com-discoverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-discoverability-api-openapi.yml
- filename: astraverify-com-email-api-openapi.yml
  format: yaml
  label: AstraVerify Email API
  slug: astraverify-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-email-api-openapi.yml
- filename: astraverify-com-fetch-as-api-openapi.yml
  format: yaml
  label: AstraVerify Fetch As API
  slug: astraverify-com-fetch-as-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-fetch-as-api-openapi.yml
- filename: astraverify-com-report-api-openapi.yml
  format: yaml
  label: AstraVerify Report API
  slug: astraverify-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-report-api-openapi.yml
- filename: astraverify-com-verify-api-openapi.yml
  format: yaml
  label: AstraVerify Verify API
  slug: astraverify-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-verify-api-openapi.yml
claim_count: 3
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
  - summary: Unpermitted bulk or automated use
    text: Automated or bulk use of the scan endpoints without written permission is not allowed.
  - summary: Crawler features
    text: By using these features you confirm you understand this.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customers do not create passwords. Your history and orders are reached through a signed link emailed to the address used at checkout
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AstraVerify
provenance_date: '2026-11-09'
provider_name: AstraVerify
provider_slug: astraverify-com
slug: astraverify-com-eligibility
source_date: '2026-11-09'
source_filename: astraverify-com-eligibility.yml
source_heading: Eligibility
source_page: https://astraverify.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AstraVerify\naid: astraverify-com\nurl: https://astraverify.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unpermitted bulk or automated use\n  text: Automated or bulk use of the scan endpoints without written permission is not allowed.\n- summary: Crawler features\n  text: By using these features you confirm you understand this.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customers do not create passwords. Your history and orders are reached through a signed link emailed to\n    the\
  \ address used at checkout\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astraverify-com/eligibility/astraverify-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from AstraVerify's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Email
- Artificial Intelligence
- Discoverability
- Domain
---
