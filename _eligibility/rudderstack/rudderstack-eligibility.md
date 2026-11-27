---
api_specs:
- filename: rudderstack-event-streaming-asyncapi.yml
  format: yaml
  label: RudderStack Webhook Source API
  slug: rudderstack-webhook-source-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/rudderstack/asyncapi/rudderstack-event-streaming-asyncapi.yml
- filename: rudderstack-http-api-api-openapi.yml
  format: yaml
  label: RudderStack HTTP API
  slug: rudderstack-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-http-api-api-openapi.yml
- filename: rudderstack-internal-api-api-openapi.yml
  format: yaml
  label: RudderStack Internal API
  slug: rudderstack-internal-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rudderstack/openapi/rudderstack-internal-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents that it is acquiring the Services for business purposes and not for personal, family, or household purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive personal data
    text: collect, transmit or provide to the Services hereunder any payment card, bank account, or other financial account information, or any medical information of any nature, including bio-metric or genetic data
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
name: RudderStack
provenance_date: '2026-11-10'
provider_name: RudderStack
provider_slug: rudderstack
slug: rudderstack-eligibility
source_date: '2026-11-10'
source_filename: rudderstack-eligibility.yml
source_heading: Eligibility
source_page: https://www.rudderstack.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RudderStack\naid: rudderstack\nurl: https://www.rudderstack.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer represents that it is acquiring the Services for business purposes and not for personal, family,\n    or household purposes.\nrestricted_uses:\n- summary: No sensitive personal data\n  text: collect, transmit or provide to the Services hereunder any payment card, bank account, or other financial\n    account information, or any medical information of any nature, including bio-metric\
  \ or genetic data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rudderstack/eligibility/rudderstack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from RudderStack's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Data Pipeline
- Open Source
- Event Streaming
- Reverse ETL
- Analytics
- Identity Resolution
---
