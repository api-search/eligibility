---
api_specs:
- filename: emailoctopus-automation-api-openapi.yml
  format: yaml
  label: EmailOctopus Automation API
  slug: emailoctopus-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-automation-api-openapi.yml
- filename: emailoctopus-campaign-api-openapi.yml
  format: yaml
  label: EmailOctopus Campaign API
  slug: emailoctopus-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-campaign-api-openapi.yml
- filename: emailoctopus-contact-api-openapi.yml
  format: yaml
  label: EmailOctopus Contact API
  slug: emailoctopus-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-contact-api-openapi.yml
- filename: emailoctopus-field-api-openapi.yml
  format: yaml
  label: EmailOctopus Field API
  slug: emailoctopus-field-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-field-api-openapi.yml
- filename: emailoctopus-list-api-openapi.yml
  format: yaml
  label: EmailOctopus List API
  slug: emailoctopus-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-list-api-openapi.yml
- filename: emailoctopus-tag-api-openapi.yml
  format: yaml
  label: EmailOctopus Tag API
  slug: emailoctopus-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-tag-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: EmailOctopus is built for organisations, and we ask you to use it for purposes relating to your trade, business, craft or profession.
    type: business
  - text: You are a consumer if you are an individual acquiring the Subscription wholly or mainly outside your trade, business, craft or profession
    type: individual
  minimum_age:
    text: The Platform is not available to any person under the age of 18 or any person who has previously been suspended or prohibited from using the Platform.
    value: '18'
  restricted_uses:
  - summary: Special category data
    text: not use the Service to send or receive any special category personal data or personal data relating to criminal convictions and offences
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we may, in our absolute discretion, choose to accept you as a registered user within the Service and provide you with an Account. We vet accounts before and during use of the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EmailOctopus
provenance_date: '2026-11-09'
provider_name: EmailOctopus
provider_slug: emailoctopus
slug: emailoctopus-eligibility
source_date: '2026-11-09'
source_filename: emailoctopus-eligibility.yml
source_heading: Eligibility
source_page: https://emailoctopus.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EmailOctopus\naid: emailoctopus\nurl: https://emailoctopus.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: EmailOctopus is built for organisations, and we ask you to use it for purposes relating to your trade, business,\n    craft or profession.\n- type: individual\n  text: You are a consumer if you are an individual acquiring the Subscription wholly or mainly outside your trade,\n    business, craft or profession\nrestricted_uses:\n- summary: Special category data\n  text: not use the Service to send\
  \ or receive any special category personal data or personal data relating to criminal\n    convictions and offences\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we may, in our absolute discretion, choose to accept you as a registered user within the Service and provide\n    you with an Account. We vet accounts before and during use of the Service\nminimum_age:\n  value: '18'\n  text: The Platform is not available to any person under the age of 18 or any person who has previously been suspended\n    or prohibited from using the Platform.\n"
source_yaml_url: https://artifacts.apis.io/emailoctopus/eligibility/emailoctopus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from EmailOctopus's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Email Marketing
- Newsletters
- Campaigns
- Automation
- Contacts
- List
- Marketing
- Webhook
- Transactional Email
- Subscriber Management
- Reporting
---
