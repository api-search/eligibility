---
api_specs:
- filename: simpletexting-campaigns-api-openapi.yml
  format: yaml
  label: SimpleTexting Campaigns API
  slug: simpletexting-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-campaigns-api-openapi.yml
- filename: simpletexting-contact-lists-api-openapi.yml
  format: yaml
  label: SimpleTexting Contact Lists API
  slug: simpletexting-contact-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-contact-lists-api-openapi.yml
- filename: simpletexting-contact-segments-api-openapi.yml
  format: yaml
  label: SimpleTexting Contact Segments API
  slug: simpletexting-contact-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-contact-segments-api-openapi.yml
- filename: simpletexting-contacts-api-openapi.yml
  format: yaml
  label: SimpleTexting Contacts API
  slug: simpletexting-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-contacts-api-openapi.yml
- filename: simpletexting-contacts-batch-operations-api-openapi.yml
  format: yaml
  label: SimpleTexting Contacts - Batch Operations API
  slug: simpletexting-contacts-batch-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-contacts-batch-operations-api-openapi.yml
- filename: simpletexting-custom-fields-api-openapi.yml
  format: yaml
  label: SimpleTexting Custom Fields API
  slug: simpletexting-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-custom-fields-api-openapi.yml
- filename: simpletexting-media-items-api-openapi.yml
  format: yaml
  label: SimpleTexting Media Items API
  slug: simpletexting-media-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-media-items-api-openapi.yml
- filename: simpletexting-messages-api-openapi.yml
  format: yaml
  label: SimpleTexting Messages API
  slug: simpletexting-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-messages-api-openapi.yml
- filename: simpletexting-tenant-api-openapi.yml
  format: yaml
  label: SimpleTexting Tenant API
  slug: simpletexting-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-tenant-api-openapi.yml
- filename: simpletexting-webhooks-api-openapi.yml
  format: yaml
  label: SimpleTexting Webhooks API
  slug: simpletexting-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-webhooks-api-openapi.yml
- filename: simpletexting-tenant-phones-api-openapi.yml
  format: yaml
  label: SimpleTexting Tenant phones API
  slug: simpletexting-tenant-phones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-tenant-phones-api-openapi.yml
- filename: simpletexting-webhook-reports-api-openapi.yml
  format: yaml
  label: SimpleTexting Webhook Reports API
  slug: simpletexting-webhook-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpletexting/openapi/simpletexting-webhook-reports-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: Children under the age of 13 may not sign up for an SimpleTexting account or use any SimpleTexting services.
    value: '13'
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
name: SimpleTexting
provenance_date: '2026-11-10'
provider_name: SimpleTexting
provider_slug: simpletexting
slug: simpletexting-eligibility
source_date: '2026-11-10'
source_filename: simpletexting-eligibility.yml
source_heading: Eligibility
source_page: https://simpletexting.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimpleTexting\naid: simpletexting\nurl: https://simpletexting.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are of legal age to form a binding contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children under the age of 13 may not sign up for an SimpleTexting account or use any SimpleTexting services.\n"
source_yaml_url: https://artifacts.apis.io/simpletexting/eligibility/simpletexting-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from SimpleTexting's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- MMS
- Messaging
- Marketing
- Text Messaging
- SMS Marketing
- Communications
- Campaigns
- Contacts
- Webhook
- A2P 10DLC
---
