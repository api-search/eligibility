---
api_specs:
- filename: qlik-cloud-api-keys-api-openapi.yml
  format: yaml
  label: Qlik Cloud Api Keys API
  slug: qlik-cloud-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-api-keys-api-openapi.yml
- filename: qlik-cloud-apps-api-openapi.yml
  format: yaml
  label: Qlik Cloud Apps API
  slug: qlik-cloud-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-apps-api-openapi.yml
- filename: qlik-cloud-csrf-token-api-openapi.yml
  format: yaml
  label: Qlik Cloud Csrf Token API
  slug: qlik-cloud-csrf-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-csrf-token-api-openapi.yml
- filename: qlik-cloud-spaces-api-openapi.yml
  format: yaml
  label: Qlik Cloud Spaces API
  slug: qlik-cloud-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-spaces-api-openapi.yml
- filename: qlik-cloud-users-api-openapi.yml
  format: yaml
  label: Qlik Cloud Users API
  slug: qlik-cloud-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-users-api-openapi.yml
- filename: qlik-cloud-webhooks-api-openapi.yml
  format: yaml
  label: Qlik Cloud Webhooks API
  slug: qlik-cloud-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qlik-cloud/openapi/qlik-cloud-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must ... not live in an area in which use of the Qlik Sites is prohibited by applicable law.
  entity_types:
  - text: if you access the Qlik Sites on behalf of a legal entity, to that entity.
    type: business
  minimum_age:
    text: You must be at least sixteen (16) years old to have a Qlik Account
    value: '16'
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
name: Qlik Cloud
provenance_date: '2026-11-10'
provider_name: Qlik Cloud
provider_slug: qlik-cloud
slug: qlik-cloud-eligibility
source_date: '2026-11-10'
source_filename: qlik-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.qlik.com/us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qlik Cloud\naid: qlik-cloud\nurl: https://www.qlik.com/us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must ... not live in an area in which use of the Qlik Sites is prohibited by applicable law.\nentity_types:\n- type: business\n  text: if you access the Qlik Sites on behalf of a legal entity, to that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least sixteen (16) years old to have a Qlik Account\n"
source_yaml_url: https://artifacts.apis.io/qlik-cloud/eligibility/qlik-cloud-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Qlik Cloud's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Cloud
- Data Integration
- Software-as-a-Service
- Visualization
- Data Visualization
---
