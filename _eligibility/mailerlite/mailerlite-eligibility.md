---
api_specs:
- filename: mailerlite-webhook-api-openapi.yml
  format: yaml
  label: MailerLite Webhook API
  slug: mailerlite-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailerlite/openapi/mailerlite-webhook-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we do not provide Services or accept payments from Customers who are registered in any country or region sanctioned by the United States, United Kingdom, European Union, or United Nations.
  entity_types:
  - text: use the Services solely for purposes relating to your trade, business, craft, or profession as these Services are not intended for personal use
    type: business
  - text: the entity or person accessing any Services ("Customer" or "you")
    type: individual
  minimum_age:
    text: be at least sixteen years old
    value: '16'
  restricted_uses:
  - summary: Prohibited content types
    text: 'You cannot send: pornography, escort; affiliate marketing, pyramid schemes, multi-level-marketing (MLM)'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If you comply with our rules then we will approve your account and you’ll receive an email notification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MailerLite
provenance_date: '2026-11-10'
provider_name: MailerLite
provider_slug: mailerlite
slug: mailerlite-eligibility
source_date: '2026-11-10'
source_filename: mailerlite-eligibility.yml
source_heading: Eligibility
source_page: https://www.mailerlite.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MailerLite\naid: mailerlite\nurl: https://www.mailerlite.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we do not provide Services or accept payments from Customers who are registered in any country or region\n    sanctioned by the United States, United Kingdom, European Union, or United Nations.\nentity_types:\n- type: business\n  text: use the Services solely for purposes relating to your trade, business, craft, or profession as these Services\n    are not intended for personal use\n- type: individual\n  text: the entity or person accessing any Services\
  \ (\"Customer\" or \"you\")\nrestricted_uses:\n- summary: Prohibited content types\n  text: 'You cannot send: pornography, escort; affiliate marketing, pyramid schemes, multi-level-marketing (MLM)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If you comply with our rules then we will approve your account and you’ll receive an email notification.\nminimum_age:\n  value: '16'\n  text: be at least sixteen years old\n"
source_yaml_url: https://artifacts.apis.io/mailerlite/eligibility/mailerlite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from MailerLite's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- Automation
- Newsletters
- Subscribers
- Campaigns
- Webhook
- E-Commerce
- Segmentation
- Transactional Email
- MCP
- Email
---
