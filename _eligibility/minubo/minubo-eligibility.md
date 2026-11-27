---
api_specs:
- filename: minubo-auth-api-openapi.yml
  format: yaml
  label: Minubo Auth API
  slug: minubo-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-auth-api-openapi.yml
- filename: minubo-data-api-openapi.yml
  format: yaml
  label: Minubo Data API
  slug: minubo-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-data-api-openapi.yml
- filename: minubo-etl-api-openapi.yml
  format: yaml
  label: Minubo ETL API
  slug: minubo-etl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-etl-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: die Gesellschaft oder die Organisation oder den Unternehmer, der oder die ein Abonnement der Datenplattform erwirbt
    type: business
  minimum_age:
    text: null
    value: null
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
name: Minubo
provenance_date: '2026-11-10'
provider_name: Minubo
provider_slug: minubo
slug: minubo-eligibility
source_date: '2026-11-10'
source_filename: minubo-eligibility.yml
source_heading: Eligibility
source_page: https://www.minubo.com/de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minubo\naid: minubo\nurl: https://www.minubo.com/de/agb\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: die Gesellschaft oder die Organisation oder den Unternehmer, der oder die ein Abonnement der Datenplattform\n    erwirbt\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/minubo/eligibility/minubo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Minubo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Business Intelligence
- Analytics
- Retail
- Data
- ETL
- Reporting
---
