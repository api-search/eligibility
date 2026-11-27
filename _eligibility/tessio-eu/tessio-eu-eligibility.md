---
api_specs:
- filename: tessio-eu-age-verification-api-openapi.yml
  format: yaml
  label: tessio-eu Age Verification API
  slug: tessio-eu-age-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-age-verification-api-openapi.yml
- filename: tessio-eu-stats-api-openapi.yml
  format: yaml
  label: tessio-eu Stats API
  slug: tessio-eu-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-stats-api-openapi.yml
- filename: tessio-eu-webhooks-api-openapi.yml
  format: yaml
  label: tessio-eu Webhooks API
  slug: tessio-eu-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-webhooks-api-openapi.yml
claim_count: 2
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
  - summary: Harassment, surveillance, discrimination
    text: Do not use it to harass, surveil or discriminate.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Before we enable it you must confirm the email address on your account, and we must approve the organisation, which we do after we understand what you are building.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tessio-eu
provenance_date: '2026-11-10'
provider_name: tessio-eu
provider_slug: tessio-eu
slug: tessio-eu-eligibility
source_date: '2026-11-10'
source_filename: tessio-eu-eligibility.yml
source_heading: Eligibility
source_page: https://tessio.eu/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tessio-eu\naid: tessio-eu\nurl: https://tessio.eu/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment, surveillance, discrimination\n  text: Do not use it to harass, surveil or discriminate.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Before we enable it you must confirm the email address on your account, and we must approve the organisation,\n    which we do after we understand what you are building.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tessio-eu/eligibility/tessio-eu-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from tessio-eu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Age Verification
- EU
- Identity
---
