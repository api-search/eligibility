---
api_specs:
- filename: customermates-com-addresses-api-openapi.yml
  format: yaml
  label: Customermates Addresses API
  slug: customermates-com-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-addresses-api-openapi.yml
- filename: customermates-com-data-views-api-openapi.yml
  format: yaml
  label: Customermates Data Views API
  slug: customermates-com-data-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-data-views-api-openapi.yml
- filename: customermates-com-files-api-openapi.yml
  format: yaml
  label: Customermates Files API
  slug: customermates-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-files-api-openapi.yml
- filename: customermates-com-knowledge-base-api-openapi.yml
  format: yaml
  label: Customermates Knowledge Base API
  slug: customermates-com-knowledge-base-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-knowledge-base-api-openapi.yml
- filename: customermates-com-members-api-openapi.yml
  format: yaml
  label: Customermates Members API
  slug: customermates-com-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-members-api-openapi.yml
- filename: customermates-com-messaging-api-openapi.yml
  format: yaml
  label: Customermates Messaging API
  slug: customermates-com-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-messaging-api-openapi.yml
- filename: customermates-com-operations-api-openapi.yml
  format: yaml
  label: Customermates Operations API
  slug: customermates-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-operations-api-openapi.yml
- filename: customermates-com-record-links-api-openapi.yml
  format: yaml
  label: Customermates Record Links API
  slug: customermates-com-record-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-record-links-api-openapi.yml
- filename: customermates-com-records-api-openapi.yml
  format: yaml
  label: Customermates Records API
  slug: customermates-com-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-records-api-openapi.yml
- filename: customermates-com-roles-api-openapi.yml
  format: yaml
  label: Customermates Roles API
  slug: customermates-com-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-roles-api-openapi.yml
- filename: customermates-com-routines-api-openapi.yml
  format: yaml
  label: Customermates Routines API
  slug: customermates-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-routines-api-openapi.yml
- filename: customermates-com-trash-api-openapi.yml
  format: yaml
  label: Customermates Trash API
  slug: customermates-com-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-trash-api-openapi.yml
- filename: customermates-com-users-api-openapi.yml
  format: yaml
  label: Customermates Users API
  slug: customermates-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-users-api-openapi.yml
- filename: customermates-com-webhooks-api-openapi.yml
  format: yaml
  label: Customermates Webhooks API
  slug: customermates-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-webhooks-api-openapi.yml
- filename: customermates-com-widgets-api-openapi.yml
  format: yaml
  label: Customermates Widgets API
  slug: customermates-com-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/customermates-com/openapi/customermates-com-widgets-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The managed service is offered worldwide exclusively to business customers that enter into the contract for purposes of their trade, business, craft, or self-employed professional activity.
  entity_types:
  - text: The managed service is offered worldwide exclusively to business customers that enter into the contract for purposes of their trade, business, craft, or self-employed professional activity.
    type: business
  - text: This includes entrepreneurs within the meaning of § 14 BGB, legal entities under public law, and special funds under public law; it excludes consumers acting mainly outside such an activity.
    type: government
  minimum_age:
    text: Each person who uses Mate must be at least 16 years old or the minimum age required in that person's country to consent to use the service.
    value: '16'
  restricted_uses:
  - summary: No legally or materially impactful decisions with Mate
    text: Mate and any output about a person must not be used for any purpose that could have a legal or material impact on that person, including decisions concerning credit, education, employment, housing, insurance, legal matters, or medical matters.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Provider may request evidence of business status and may terminate the contract for cause if the customer is in fact acting as a consumer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Customermates
provenance_date: '2026-11-09'
provider_name: Customermates
provider_slug: customermates-com
slug: customermates-com-eligibility
source_date: '2026-11-09'
source_filename: customermates-com-eligibility.yml
source_heading: Eligibility
source_page: https://customermates.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Customermates\naid: customermates-com\nurl: https://customermates.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The managed service is offered worldwide exclusively to business customers that enter into the contract\n    for purposes of their trade, business, craft, or self-employed professional activity.\nentity_types:\n- type: business\n  text: The managed service is offered worldwide exclusively to business customers that enter into the contract\n    for purposes of their trade, business, craft, or self-employed professional activity.\n- type: government\n  text:\
  \ This includes entrepreneurs within the meaning of § 14 BGB, legal entities under public law, and special\n    funds under public law; it excludes consumers acting mainly outside such an activity.\nrestricted_uses:\n- summary: No legally or materially impactful decisions with Mate\n  text: Mate and any output about a person must not be used for any purpose that could have a legal or material\n    impact on that person, including decisions concerning credit, education, employment, housing, insurance, legal\n    matters, or medical matters.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Provider may request evidence of business status and may terminate the contract for cause if the customer\n    is in fact acting as a consumer.\nminimum_age:\n  value: '16'\n  text: Each person who uses Mate must be at least 16 years old or the minimum age required in that person's country\n    to consent to use the service.\n"
source_yaml_url: https://artifacts.apis.io/customermates-com/eligibility/customermates-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Customermates's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Open Source
- Artificial Intelligence
- Software-as-a-Service
---
