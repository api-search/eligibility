---
api_specs:
- filename: medigo-attachments-api-openapi.yml
  format: yaml
  label: Medigo Attachments API
  slug: medigo-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-attachments-api-openapi.yml
- filename: medigo-inquiries-api-openapi.yml
  format: yaml
  label: Medigo Inquiries API
  slug: medigo-inquiries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-inquiries-api-openapi.yml
- filename: medigo-search-api-openapi.yml
  format: yaml
  label: Medigo Search API
  slug: medigo-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-search-api-openapi.yml
- filename: medigo-second-opinions-api-openapi.yml
  format: yaml
  label: Medigo Second Opinions API
  slug: medigo-second-opinions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-second-opinions-api-openapi.yml
- filename: medigo-tpa-api-openapi.yml
  format: yaml
  label: Medigo Tpa API
  slug: medigo-tpa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-tpa-api-openapi.yml
- filename: medigo-webhooks-api-openapi.yml
  format: yaml
  label: Medigo Webhooks API
  slug: medigo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Services delivered to insurer, reinsurer, TPA, and corporate clients are governed by separate written agreements, not by these terms.
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
name: Medigo
provenance_date: '2026-11-10'
provider_name: Medigo
provider_slug: medigo
slug: medigo-eligibility
source_date: '2026-11-10'
source_filename: medigo-eligibility.yml
source_heading: Eligibility
source_page: https://www.medigo.com/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medigo\naid: medigo\nurl: https://www.medigo.com/en/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Services delivered to insurer, reinsurer, TPA, and corporate clients are governed by separate written agreements,\n    not by these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/medigo/eligibility/medigo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Medigo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Healthcare
- Insurance
- Third-Party Administrator
- Claims
- Cost Containment
- Second Medical Opinion
- Medical Travel
- Health Insurance
---
