---
api_specs:
- filename: hotel-engine-catalogservice-api-openapi.yml
  format: yaml
  label: Engine Catalog Service API
  slug: hotel-engine-catalogservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-catalogservice-api-openapi.yml
- filename: hotel-engine-lodgingbookingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Booking Service API
  slug: hotel-engine-lodgingbookingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingbookingservice-api-openapi.yml
- filename: hotel-engine-lodgingshoppingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Shopping Service API
  slug: hotel-engine-lodgingshoppingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingshoppingservice-api-openapi.yml
- filename: hotel-engine-content-service-api-openapi.yml
  format: yaml
  label: Engine Content Service API
  slug: hotel-engine-content-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-content-service-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals who are 18 years and older and who can form legally binding contracts under applicable law may become a Member, Administrator, or User
    type: individual
  minimum_age:
    text: I am at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Access prohibited where unlawful
    text: ACCESS TO THE SITE (OR PORTIONS THEREOF) AND THE USE OF INFORMATION, MATERIALS, OR SERVICES PROVIDED THROUGH THE SITE (OR PORTIONS THEREOF), ARE NOT INTENDED, AND ARE PROHIBITED, WHERE SUCH ACCESS OR USE VIOLATES APPLICABLE LAWS OR REGULATIONS.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Engine reserves the right, in its sole discretion, to reject any application to become a Member.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Engine
provenance_date: '2026-11-09'
provider_name: Engine
provider_slug: hotel-engine
slug: hotel-engine-eligibility
source_date: '2026-11-09'
source_filename: hotel-engine-eligibility.yml
source_heading: Eligibility
source_page: https://engine.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Engine\naid: hotel-engine\nurl: https://engine.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals who are 18 years and older and who can form legally binding contracts under applicable\n    law may become a Member, Administrator, or User\nrestricted_uses:\n- summary: Access prohibited where unlawful\n  text: ACCESS TO THE SITE (OR PORTIONS THEREOF) AND THE USE OF INFORMATION, MATERIALS, OR SERVICES PROVIDED THROUGH\n    THE SITE (OR PORTIONS THEREOF), ARE NOT INTENDED, AND ARE PROHIBITED,\
  \ WHERE SUCH ACCESS OR USE VIOLATES APPLICABLE\n    LAWS OR REGULATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Engine reserves the right, in its sole discretion, to reject any application to become a Member.\nminimum_age:\n  value: '18'\n  text: I am at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/hotel-engine/eligibility/hotel-engine-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Engine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Business Travel
- Lodging
- Hotels
- Booking
- Travel Management
- Expense Management
- Payments
- gRPC
- Protobuf
- Partner API
---
