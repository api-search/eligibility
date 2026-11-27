---
api_specs:
- filename: tenderapi-eu-organisations-api-openapi.yml
  format: yaml
  label: tenderapi-eu Organisations API
  slug: tenderapi-eu-organisations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-eu/openapi/tenderapi-eu-organisations-api-openapi.yml
- filename: tenderapi-eu-tenders-api-openapi.yml
  format: yaml
  label: tenderapi-eu Tenders API
  slug: tenderapi-eu-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenderapi-eu/openapi/tenderapi-eu-tenders-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is offered exclusively to businesses, public bodies and professionals acting in the course of their trade, business or profession.
    type: business
  - text: The Service is offered exclusively to businesses, public bodies and professionals acting in the course of their trade, business or profession.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Service for anything unlawful, fraudulent or infringing
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
name: tenderapi-eu
provenance_date: '2026-11-10'
provider_name: tenderapi-eu
provider_slug: tenderapi-eu
slug: tenderapi-eu-eligibility
source_date: '2026-11-10'
source_filename: tenderapi-eu-eligibility.yml
source_heading: Eligibility
source_page: https://tenderapi.eu/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tenderapi-eu\naid: tenderapi-eu\nurl: https://tenderapi.eu/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is offered exclusively to businesses, public bodies and professionals acting in the course of\n    their trade, business or profession.\n- type: government\n  text: The Service is offered exclusively to businesses, public bodies and professionals acting in the course of\n    their trade, business or profession.\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Service for anything unlawful,\
  \ fraudulent or infringing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tenderapi-eu/eligibility/tenderapi-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from tenderapi-eu's own page on 2026-11-10.
synthetic: false
tags:
- EU
- Procurement
- Tenders
- Data
---
