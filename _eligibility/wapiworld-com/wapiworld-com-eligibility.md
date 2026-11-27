---
api_specs:
- filename: wapiworld-com-instances-api-openapi.yml
  format: yaml
  label: wapiworld-com Instances API
  slug: wapiworld-com-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wapiworld-com/openapi/wapiworld-com-instances-api-openapi.yml
- filename: wapiworld-com-messages-api-openapi.yml
  format: yaml
  label: wapiworld-com Messages API
  slug: wapiworld-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wapiworld-com/openapi/wapiworld-com-messages-api-openapi.yml
- filename: wapiworld-com-projects-api-openapi.yml
  format: yaml
  label: wapiworld-com Projects API
  slug: wapiworld-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wapiworld-com/openapi/wapiworld-com-projects-api-openapi.yml
- filename: wapiworld-com-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: wapiworld-com Webhook subscriptions API
  slug: wapiworld-com-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wapiworld-com/openapi/wapiworld-com-webhook-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for a business or another organization, you must have authority to bind it. A business customer uses the Service for a trade, business, craft, or profession; a consumer uses it mainly for personal purposes.
    type: business
  - text: A consumer uses it mainly for personal purposes.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Do not use the Service to break the law, infringe another person's rights, impersonate others, harass or discriminate, or submit unlawful, harmful, infringing, or deceptive content.
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
name: wapiworld-com
provenance_date: '2026-11-10'
provider_name: wapiworld-com
provider_slug: wapiworld-com
slug: wapiworld-com-eligibility
source_date: '2026-11-10'
source_filename: wapiworld-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.wapiworld.com/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wapiworld-com\naid: wapiworld-com\nurl: https://www.wapiworld.com/en/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for a business or another organization, you must have authority to bind it. A business customer\n    uses the Service for a trade, business, craft, or profession; a consumer uses it mainly for personal purposes.\n- type: individual\n  text: A consumer uses it mainly for personal purposes.\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Do not use the Service to break the\
  \ law, infringe another person's rights, impersonate others, harass or\n    discriminate, or submit unlawful, harmful, infringing, or deceptive content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wapiworld-com/eligibility/wapiworld-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from wapiworld-com's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- WhatsApp
- Developer Platform
- Communications
---
