---
api_specs:
- filename: luminary-documents-api-openapi.yml
  format: yaml
  label: Luminary Documents API
  slug: luminary-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-documents-api-openapi.yml
- filename: luminary-entities-api-openapi.yml
  format: yaml
  label: Luminary Entities API
  slug: luminary-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-entities-api-openapi.yml
- filename: luminary-households-api-openapi.yml
  format: yaml
  label: Luminary Households API
  slug: luminary-households-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-households-api-openapi.yml
- filename: luminary-individuals-api-openapi.yml
  format: yaml
  label: Luminary Individuals API
  slug: luminary-individuals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-individuals-api-openapi.yml
- filename: luminary-users-api-openapi.yml
  format: yaml
  label: Luminary Users API
  slug: luminary-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-users-api-openapi.yml
- filename: luminary-valuations-api-openapi.yml
  format: yaml
  label: Luminary Valuations API
  slug: luminary-valuations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/luminary/openapi/luminary-valuations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
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
name: Luminary
provenance_date: '2026-11-10'
provider_name: Luminary
provider_slug: luminary
slug: luminary-eligibility
source_date: '2026-11-10'
source_filename: luminary-eligibility.yml
source_heading: Eligibility
source_page: https://withluminary.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luminary\naid: luminary\nurl: https://withluminary.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/luminary/eligibility/luminary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Luminary's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Estate Planning
- Wealth Management
- Financial Services
- Legal Tech
- Document AI
- Family Office
- OAuth
- Authentication
---
