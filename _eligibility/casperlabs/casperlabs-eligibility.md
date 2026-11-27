---
api_specs:
- filename: casperlabs-casperlabs-api-api-openapi.yml
  format: yaml
  label: Casperlabs Casperlabs API
  slug: casperlabs-casperlabs-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casperlabs/openapi/casperlabs-casperlabs-api-api-openapi.yml
- filename: casperlabs-metrics-api-openapi.yml
  format: yaml
  label: Casperlabs Metrics API
  slug: casperlabs-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casperlabs/openapi/casperlabs-metrics-api-openapi.yml
- filename: casperlabs-status-api-openapi.yml
  format: yaml
  label: Casperlabs Status API
  slug: casperlabs-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casperlabs/openapi/casperlabs-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CH
    text: We provide this Website for use only by person located in Switzerland.
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
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
name: Casperlabs
provenance_date: '2026-11-09'
provider_name: Casperlabs
provider_slug: casperlabs
slug: casperlabs-eligibility
source_date: '2026-11-09'
source_filename: casperlabs-eligibility.yml
source_heading: Eligibility
source_page: https://www.casper.network/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Casperlabs\naid: casperlabs\nurl: https://www.casper.network/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CH\n  excluded: []\n  text: We provide this Website for use only by person located in Switzerland.\nentity_types: []\nrestricted_uses:\n- summary: Commercial purposes\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users\
  \ who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/casperlabs/eligibility/casperlabs-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Casperlabs's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Smart Contracts
- Enterprise
- AI-Toolkit
- Decentralized Finance
---
