---
api_specs:
- filename: postscript-subscribers-api-openapi.yml
  format: yaml
  label: Postscript Subscribers API
  slug: postscript-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-subscribers-api-openapi.yml
- filename: postscript-events-api-openapi.yml
  format: yaml
  label: Postscript Events API
  slug: postscript-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-events-api-openapi.yml
- filename: postscript-keywords-api-openapi.yml
  format: yaml
  label: Postscript Keywords API
  slug: postscript-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-keywords-api-openapi.yml
- filename: postscript-messages-api-openapi.yml
  format: yaml
  label: Postscript Messages API
  slug: postscript-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-messages-api-openapi.yml
- filename: postscript-webhooks-api-openapi.yml
  format: yaml
  label: Postscript Webhooks API
  slug: postscript-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-webhooks-api-openapi.yml
- filename: postscript-compliance-api-openapi.yml
  format: yaml
  label: Postscript Compliance API
  slug: postscript-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-compliance-api-openapi.yml
- filename: postscript-identity-api-openapi.yml
  format: yaml
  label: Postscript Identity API
  slug: postscript-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postscript/openapi/postscript-identity-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the API, you must be 18 years of age or older, capable of forming a binding contract with Postscript
    type: individual
  - text: If you access or use the API on behalf of an entity, you represent and warrant that you have the authority to bind that entity to these API Terms
    type: business
  - source: https://postscript.io/terms-of-service
    text: If you access or use the Postscript Services on behalf of an entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: To use the API, you must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No processing of sensitive or regulated data categories
    text: The API and Postscript Platform Services are not intended for processing any of the foregoing prohibited data categories.
  - source: https://postscript.io/terms-of-service
    summary: Sensitive data prohibited
    text: Customer Data may not include any of the following categories of data
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
name: Postscript
provenance_date: '2026-11-10'
provider_name: Postscript
provider_slug: postscript
slug: postscript-eligibility
source_date: '2026-11-10'
source_filename: postscript-eligibility.yml
source_heading: Eligibility
source_page: https://postscript.io/api-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Postscript\naid: postscript\nurl: https://postscript.io/api-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://postscript.io/api-terms-of-service\n  - https://postscript.io/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the API, you must be 18 years of age or older, capable of forming a binding contract with Postscript\n- type: business\n  text: If you access or use the API on behalf of an entity, you represent and warrant that you have the authority\n    to bind that entity to these API Terms\n- type: business\n  text:\
  \ If you access or use the Postscript Services on behalf of an entity, you represent and warrant that you\n    have the authority to bind that entity to these Terms\n  source: https://postscript.io/terms-of-service\nrestricted_uses:\n- summary: No processing of sensitive or regulated data categories\n  text: The API and Postscript Platform Services are not intended for processing any of the foregoing prohibited\n    data categories.\n- summary: Sensitive data prohibited\n  text: Customer Data may not include any of the following categories of data\n  source: https://postscript.io/terms-of-service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the API, you must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/postscript/eligibility/postscript-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Postscript's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- Marketing
- Messaging
- E-Commerce
- Shopify
- RCS
- Subscribers
- Webhook
- Compliance
---
