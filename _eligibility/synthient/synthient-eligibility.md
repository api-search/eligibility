---
api_specs:
- filename: synthient-account-api-openapi.yml
  format: yaml
  label: Synthient API Account API
  slug: synthient-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-account-api-openapi.yml
- filename: synthient-anonymizers-api-openapi.yml
  format: yaml
  label: Synthient API Anonymizers API
  slug: synthient-anonymizers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-anonymizers-api-openapi.yml
- filename: synthient-helios-api-openapi.yml
  format: yaml
  label: Synthient API Helios API
  slug: synthient-helios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-helios-api-openapi.yml
- filename: synthient-ja4t-api-openapi.yml
  format: yaml
  label: Synthient API JA4T API
  slug: synthient-ja4t-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-ja4t-api-openapi.yml
- filename: synthient-lookup-api-openapi.yml
  format: yaml
  label: Synthient API Lookup API
  slug: synthient-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-lookup-api-openapi.yml
- filename: synthient-proxies-api-openapi.yml
  format: yaml
  label: Synthient API Proxies API
  slug: synthient-proxies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-proxies-api-openapi.yml
- filename: synthient-torrents-api-openapi.yml
  format: yaml
  label: Synthient API Torrents API
  slug: synthient-torrents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synthient/openapi/synthient-torrents-api-openapi.yml
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
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Pricing, usage rights, service commitments, support expectations, and approved data surfaces are confirmed during access review before production credentials are issued.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Synthient API
provenance_date: '2026-11-10'
provider_name: Synthient API
provider_slug: synthient
slug: synthient-eligibility
source_date: '2026-11-10'
source_filename: synthient-eligibility.yml
source_heading: Eligibility
source_page: https://synthient.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synthient API\naid: synthient\nurl: https://synthient.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Pricing, usage rights, service commitments, support expectations, and approved data surfaces are confirmed\n    during access review before production credentials are issued.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/synthient/eligibility/synthient-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Synthient API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- IP
- Data Enrichment
- Cybersecurity
- Data
---
