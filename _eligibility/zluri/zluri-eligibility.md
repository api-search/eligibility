---
api_specs:
- filename: zluri-data-upload-api-openapi.yml
  format: yaml
  label: Zluri Data Upload API
  slug: zluri-data-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-data-upload-api-openapi.yml
- filename: zluri-instances-api-openapi.yml
  format: yaml
  label: Zluri Instances API
  slug: zluri-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-instances-api-openapi.yml
- filename: zluri-syncs-api-openapi.yml
  format: yaml
  label: Zluri Syncs API
  slug: zluri-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-syncs-api-openapi.yml
- filename: zluri-webhooks-api-openapi.yml
  format: yaml
  label: Zluri Webhooks API
  slug: zluri-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zluri/openapi/zluri-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You expressly and implicitly represent to the Company that You are of the legal contracting age
    value: legal contracting age
  restricted_uses:
  - summary: Unauthorized system use
    text: You are strictly prohibited from unauthorized use of our systems or this Website/s
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
name: Zluri
provenance_date: '2026-11-10'
provider_name: Zluri
provider_slug: zluri
slug: zluri-eligibility
source_date: '2026-11-10'
source_filename: zluri-eligibility.yml
source_heading: Eligibility
source_page: https://www.zluri.com/policy/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zluri\naid: zluri\nurl: https://www.zluri.com/policy/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized system use\n  text: You are strictly prohibited from unauthorized use of our systems or this Website/s\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal contracting age\n  text: You expressly and implicitly represent to the Company that You are of the legal contracting age\n"
source_yaml_url: https://artifacts.apis.io/zluri/eligibility/zluri-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Zluri's own page on 2026-11-10.
synthetic: false
tags:
- Identity and Access Management
- SaaS Management
---
