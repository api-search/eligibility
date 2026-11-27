---
api_specs:
- filename: flows360-openapi-generated.yml
  format: yaml
  label: Flows360 API
  slug: flows360-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flows360/openapi/_ae-authored/flows360-openapi-generated.yml
- filename: flows360-purchase-orders-api-openapi.yml
  format: yaml
  label: Flows360 Purchase Orders API
  slug: flows360-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flows360/openapi/flows360-purchase-orders-api-openapi.yml
- filename: flows360-session-api-openapi.yml
  format: yaml
  label: Flows360 Session API
  slug: flows360-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flows360/openapi/flows360-session-api-openapi.yml
- filename: flows360-suppliers-api-openapi.yml
  format: yaml
  label: Flows360 Suppliers API
  slug: flows360-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flows360/openapi/flows360-suppliers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting for an organisation, you confirm authority to bind it. Flows360 is intended for business use .
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive regulated data
    text: Highly sensitive or specially regulated data may only be processed where the applicable Flows360 service, infrastructure and contractual arrangement expressly permit it.
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
name: Flows360
provenance_date: '2026-11-09'
provider_name: Flows360
provider_slug: flows360
slug: flows360-eligibility
source_date: '2026-11-09'
source_filename: flows360-eligibility.yml
source_heading: Eligibility
source_page: https://www.flows360.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flows360\naid: flows360\nurl: https://www.flows360.co/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting for an organisation, you confirm authority to bind it. Flows360 is intended for business use .\nrestricted_uses:\n- summary: Sensitive regulated data\n  text: Highly sensitive or specially regulated data may only be processed where the applicable Flows360 service,\n    infrastructure and contractual arrangement expressly permit it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flows360/eligibility/flows360-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Flows360's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- Workflows
- Integration
- Software-as-a-Service
---
