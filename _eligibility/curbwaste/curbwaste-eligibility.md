---
api_specs:
- filename: curbwaste-catalog-api-openapi.yml
  format: yaml
  label: Curbwaste Catalog API
  slug: curbwaste-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curbwaste/openapi/curbwaste-catalog-api-openapi.yml
- filename: curbwaste-customers-api-openapi.yml
  format: yaml
  label: Curbwaste Customers API
  slug: curbwaste-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curbwaste/openapi/curbwaste-customers-api-openapi.yml
- filename: curbwaste-locations-api-openapi.yml
  format: yaml
  label: Curbwaste Locations API
  slug: curbwaste-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curbwaste/openapi/curbwaste-locations-api-openapi.yml
- filename: curbwaste-zones-api-openapi.yml
  format: yaml
  label: Curbwaste Zones API
  slug: curbwaste-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curbwaste/openapi/curbwaste-zones-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: reproduce and use the Documentation within the United States
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Service bureau and third-party access restricted
    text: allow third parties to access or use the Software, including any use in anyapplication service provider environment, service bureau, or time-sharingarrangement
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
name: Curbwaste
provenance_date: '2026-11-09'
provider_name: Curbwaste
provider_slug: curbwaste
slug: curbwaste-eligibility
source_date: '2026-11-09'
source_filename: curbwaste-eligibility.yml
source_heading: Eligibility
source_page: https://www.curbwaste.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curbwaste\naid: curbwaste\nurl: https://www.curbwaste.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: reproduce and use the Documentation within the United States\nentity_types: []\nrestricted_uses:\n- summary: Service bureau and third-party access restricted\n  text: allow third parties to access or use the Software, including any use in anyapplication service provider\n    environment, service bureau, or time-sharingarrangement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curbwaste/eligibility/curbwaste-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Curbwaste's own page on 2026-11-09.
synthetic: false
tags:
- Waste
- Software
- Software-as-a-Service
- Logistics
- Haulers
---
