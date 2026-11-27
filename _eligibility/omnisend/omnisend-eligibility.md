---
api_specs:
- filename: omnisend-brands-api-openapi.yml
  format: yaml
  label: Omnisend Brands API
  slug: omnisend-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-brands-api-openapi.yml
- filename: omnisend-campaigns-api-openapi.yml
  format: yaml
  label: Omnisend Campaigns API
  slug: omnisend-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-campaigns-api-openapi.yml
- filename: omnisend-contacts-api-openapi.yml
  format: yaml
  label: Omnisend Contacts API
  slug: omnisend-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-contacts-api-openapi.yml
- filename: omnisend-events-api-openapi.yml
  format: yaml
  label: Omnisend Events API
  slug: omnisend-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-events-api-openapi.yml
- filename: omnisend-images-api-openapi.yml
  format: yaml
  label: Omnisend Images API
  slug: omnisend-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-images-api-openapi.yml
- filename: omnisend-products-api-openapi.yml
  format: yaml
  label: Omnisend Products API
  slug: omnisend-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-products-api-openapi.yml
- filename: omnisend-segments-api-openapi.yml
  format: yaml
  label: Omnisend Segments API
  slug: omnisend-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-segments-api-openapi.yml
- filename: omnisend-automations-api-openapi.yml
  format: yaml
  label: Omnisend Automations API
  slug: omnisend-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-automations-api-openapi.yml
- filename: omnisend-event-metadata-api-openapi.yml
  format: yaml
  label: Omnisend Event Metadata API
  slug: omnisend-event-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-event-metadata-api-openapi.yml
- filename: omnisend-batch-api-openapi.yml
  format: yaml
  label: Omnisend Batch API
  slug: omnisend-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-batch-api-openapi.yml
- filename: omnisend-email-content-api-openapi.yml
  format: yaml
  label: Omnisend Email Content API
  slug: omnisend-email-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-email-content-api-openapi.yml
- filename: omnisend-email-templates-api-openapi.yml
  format: yaml
  label: Omnisend Email Templates API
  slug: omnisend-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-email-templates-api-openapi.yml
- filename: omnisend-email-universal-layouts-api-openapi.yml
  format: yaml
  label: Omnisend Email Universal Layouts API
  slug: omnisend-email-universal-layouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-email-universal-layouts-api-openapi.yml
- filename: omnisend-product-categories-api-openapi.yml
  format: yaml
  label: Omnisend Product Categories API
  slug: omnisend-product-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-product-categories-api-openapi.yml
- filename: omnisend-reports-api-openapi.yml
  format: yaml
  label: Omnisend Reports API
  slug: omnisend-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-reports-api-openapi.yml
- filename: omnisend-statistics-api-openapi.yml
  format: yaml
  label: Omnisend Statistics API
  slug: omnisend-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omnisend/openapi/omnisend-statistics-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a person who represents a legal entity and wishes to subscribe for and subscribes to the Services for business or professional purposes
    type: business
  minimum_age:
    text: be at least eighteen (18) years old and legally capable to enter contractual relationship
    value: '18'
  restricted_uses:
  - summary: Prohibited content in campaigns
    text: You must not use the Services to send email campaigns, text messages and push notifications that link to or display nudity, obscene content, gambling related content, illegal software, viruses, sales of social media followers
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
name: Omnisend
provenance_date: '2026-11-10'
provider_name: Omnisend
provider_slug: omnisend
slug: omnisend-eligibility
source_date: '2026-11-10'
source_filename: omnisend-eligibility.yml
source_heading: Eligibility
source_page: https://www.omnisend.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omnisend\naid: omnisend\nurl: https://www.omnisend.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a person who represents a legal entity and wishes to subscribe for and subscribes to the Services for business\n    or professional purposes\nrestricted_uses:\n- summary: Prohibited content in campaigns\n  text: You must not use the Services to send email campaigns, text messages and push notifications that link to\n    or display nudity, obscene content, gambling related content, illegal software, viruses,\
  \ sales of social media\n    followers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years old and legally capable to enter contractual relationship\n"
source_yaml_url: https://artifacts.apis.io/omnisend/eligibility/omnisend-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Omnisend's own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- Marketing Automation
- E-Commerce
- SMS Marketing
- Customer Engagement
- Segmentation
- Campaigns
- Forms
- Popups
- Web Push
- Automation Workflows
- Analytics
- MCP
- Transactional Messaging
---
