---
api_specs:
- filename: clay953f-credits-api-openapi.yml
  format: yaml
  label: Clay953f Credits API
  slug: clay953f-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-credits-api-openapi.yml
- filename: clay953f-me-api-openapi.yml
  format: yaml
  label: Clay953f Me API
  slug: clay953f-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-me-api-openapi.yml
- filename: clay953f-routines-api-openapi.yml
  format: yaml
  label: Clay953f Routines API
  slug: clay953f-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-routines-api-openapi.yml
- filename: clay953f-search-api-openapi.yml
  format: yaml
  label: Clay953f Search API
  slug: clay953f-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-search-api-openapi.yml
- filename: clay953f-tables-api-openapi.yml
  format: yaml
  label: Clay953f Tables API
  slug: clay953f-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-tables-api-openapi.yml
- filename: clay953f-workflowsruns-api-openapi.yml
  format: yaml
  label: Clay953f Workflows Runs API
  slug: clay953f-workflowsruns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clay953f/openapi/clay953f-workflowsruns-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not permit Users to access the Services from a U.S. embargoed country.
  entity_types:
  - text: the business or other legal entity that accepts this Agreement or uses the Services (“ Customer ”)
    type: business
  - text: If an individual accepts this Agreement without identifying a business or other legal entity, that individual is the Customer.
    type: individual
  minimum_age:
    text: The individual accepting this Agreement represents that they are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: High risk activities
    text: The Services are not intended for High Risk Activities
  - summary: Sensitive personal data
    text: or for the uploading, requesting or otherwise processing of Sensitive Personal Data.
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
name: Clay953f
provenance_date: '2026-11-09'
provider_name: Clay953f
provider_slug: clay953f
slug: clay953f-eligibility
source_date: '2026-11-09'
source_filename: clay953f-eligibility.yml
source_heading: Eligibility
source_page: https://www.clay.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clay953f\naid: clay953f\nurl: https://www.clay.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not permit Users to access the Services from a U.S. embargoed country.\nentity_types:\n- type: business\n  text: the business or other legal entity that accepts this Agreement or uses the Services (“ Customer ”)\n- type: individual\n  text: If an individual accepts this Agreement without identifying a business or other legal entity, that individual\n    is the Customer.\nrestricted_uses:\n- summary: High risk activities\n  text: The Services are\
  \ not intended for High Risk Activities\n- summary: Sensitive personal data\n  text: or for the uploading, requesting or otherwise processing of Sensitive Personal Data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The individual accepting this Agreement represents that they are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/clay953f/eligibility/clay953f-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Clay953f's own page on 2026-11-09.
synthetic: false
tags:
- Data Marketplace
- CRM Enrichment
- AI Agents
---
