---
api_specs:
- filename: jodo-webhooks-asyncapi.yml
  format: yaml
  label: Jodo Webhooks
  slug: jodo-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/jodo/asyncapi/jodo-webhooks-asyncapi.yml
- filename: jodo-configuration-api-openapi.yml
  format: yaml
  label: Jodo Configuration API
  slug: jodo-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-configuration-api-openapi.yml
- filename: jodo-flex-api-openapi.yml
  format: yaml
  label: Jodo Flex API
  slug: jodo-flex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-flex-api-openapi.yml
- filename: jodo-pay-api-openapi.yml
  format: yaml
  label: Jodo Pay API
  slug: jodo-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-pay-api-openapi.yml
- filename: jodo-students-api-openapi.yml
  format: yaml
  label: Jodo Students API
  slug: jodo-students-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-students-api-openapi.yml
- filename: jodo-users-api-openapi.yml
  format: yaml
  label: Jodo Users API
  slug: jodo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You are a resident of India.
  entity_types:
  - text: You are above 18 (Eighteen) years of age.
    type: individual
  - text: Entities registered in accordance with Applicable laws
    type: business
  minimum_age:
    text: You are above 18 (Eighteen) years of age.
    value: '18'
  restricted_uses:
  - summary: No commercial use of platform
    text: You shall not use this Platform or its contents for any commercial purpose
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
name: Jodo
provenance_date: '2026-11-09'
provider_name: Jodo
provider_slug: jodo
slug: jodo-eligibility
source_date: '2026-11-09'
source_filename: jodo-eligibility.yml
source_heading: Eligibility
source_page: https://www.jodo.in/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jodo\naid: jodo\nurl: https://www.jodo.in/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You are a resident of India.\nentity_types:\n- type: individual\n  text: You are above 18 (Eighteen) years of age.\n- type: business\n  text: Entities registered in accordance with Applicable laws\nrestricted_uses:\n- summary: No commercial use of platform\n  text: You shall not use this Platform or its contents for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are\
  \ above 18 (Eighteen) years of age.\n"
source_yaml_url: https://artifacts.apis.io/jodo/eligibility/jodo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Jodo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Education
- Fintech
- Fee Collection
- Lending
- India
- Webhook
- ERP Integration
- Financial Services
---
