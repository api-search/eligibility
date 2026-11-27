---
api_specs:
- filename: enfuce-authorisation-request-api-api-openapi.yml
  format: yaml
  label: Enfuce Authorisation Request API
  slug: enfuce-authorisation-request-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-authorisation-request-api-api-openapi.yml
- filename: enfuce-create-card-api-openapi.yml
  format: yaml
  label: Enfuce Create Card API
  slug: enfuce-create-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-create-card-api-openapi.yml
- filename: enfuce-create-pin-control-access-token-api-openapi.yml
  format: yaml
  label: Enfuce Create PIN Control access token API
  slug: enfuce-create-pin-control-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-create-pin-control-access-token-api-openapi.yml
- filename: enfuce-get-card-api-openapi.yml
  format: yaml
  label: Enfuce Get card API
  slug: enfuce-get-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-card-api-openapi.yml
- filename: enfuce-get-card-payment-info-api-openapi.yml
  format: yaml
  label: Enfuce Get Card Payment Info API
  slug: enfuce-get-card-payment-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-card-payment-info-api-openapi.yml
- filename: enfuce-get-plastic-manufacturing-history-api-openapi.yml
  format: yaml
  label: Enfuce Get plastic manufacturing history API
  slug: enfuce-get-plastic-manufacturing-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-plastic-manufacturing-history-api-openapi.yml
- filename: enfuce-update-card-api-openapi.yml
  format: yaml
  label: Enfuce Update card API
  slug: enfuce-update-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-update-card-api-openapi.yml
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
  - summary: Unlawful or harassing use of site
    text: Use the Site to threaten, harass, libel, defame Enfuce or another person, or otherwise use the Site for any purposes or in any manner that is unlawful.
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
name: Enfuce
provenance_date: '2026-11-09'
provider_name: Enfuce
provider_slug: enfuce
slug: enfuce-eligibility
source_date: '2026-11-09'
source_filename: enfuce-eligibility.yml
source_heading: Eligibility
source_page: https://enfuce.com/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enfuce\naid: enfuce\nurl: https://enfuce.com/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harassing use of site\n  text: Use the Site to threaten, harass, libel, defame Enfuce or another person, or otherwise use the Site for\n    any purposes or in any manner that is unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enfuce/eligibility/enfuce-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Enfuce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Card Issuing
- Fintech
- API Platform
- A2A
---
