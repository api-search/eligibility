---
api_specs:
- filename: koala-io-accounts-api-openapi.yml
  format: yaml
  label: Koala Accounts API
  slug: koala-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-accounts-api-openapi.yml
- filename: koala-io-collection-api-openapi.yml
  format: yaml
  label: Koala Collection API
  slug: koala-io-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-collection-api-openapi.yml
- filename: koala-io-deletion-api-openapi.yml
  format: yaml
  label: Koala Deletion API
  slug: koala-io-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-deletion-api-openapi.yml
- filename: koala-io-sdk-api-openapi.yml
  format: yaml
  label: Koala SDK API
  slug: koala-io-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-sdk-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for the internal business purposes of Customer
    type: business
  minimum_age:
    text: null
    value: null
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
name: Koala
provenance_date: '2026-11-09'
provider_name: Koala
provider_slug: koala-io
slug: koala-io-eligibility
source_date: '2026-11-09'
source_filename: koala-io-eligibility.yml
source_heading: Eligibility
source_page: https://getkoala.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Koala\naid: koala-io\nurl: https://getkoala.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: for the internal business purposes of Customer\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/koala-io/eligibility/koala-io-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Koala's own page on 2026-11-09.
synthetic: false
tags:
- Buyer Intent
- Visitor Identification
- De-anonymization
- Data Enrichment
- Go-To-Market
- Sales Intelligence
- B2B
- A2A
---
