---
api_specs:
- filename: rijksmuseum-collection-api-openapi.yml
  format: yaml
  label: Rijksmuseum Collection API
  slug: rijksmuseum-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rijksmuseum/openapi/rijksmuseum-collection-api-openapi.yml
- filename: rijksmuseum-images-api-openapi.yml
  format: yaml
  label: Rijksmuseum Images API
  slug: rijksmuseum-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rijksmuseum/openapi/rijksmuseum-images-api-openapi.yml
- filename: rijksmuseum-object-details-api-openapi.yml
  format: yaml
  label: Rijksmuseum Object Details API
  slug: rijksmuseum-object-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rijksmuseum/openapi/rijksmuseum-object-details-api-openapi.yml
- filename: rijksmuseum-user-generated-content-api-openapi.yml
  format: yaml
  label: Rijksmuseum User Generated Content API
  slug: rijksmuseum-user-generated-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rijksmuseum/openapi/rijksmuseum-user-generated-content-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected sensitive or personal data
    text: we also ensure the protection of sensitive and confidential information, such as personal data.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: without needing to request permission
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rijksmuseum
provenance_date: '2026-11-10'
provider_name: Rijksmuseum
provider_slug: rijksmuseum
slug: rijksmuseum-eligibility
source_date: '2026-11-10'
source_filename: rijksmuseum-eligibility.yml
source_heading: Eligibility
source_page: https://data.rijksmuseum.nl/policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rijksmuseum\naid: rijksmuseum\nurl: https://data.rijksmuseum.nl/policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Protected sensitive or personal data\n  text: we also ensure the protection of sensitive and confidential information, such as personal data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: without needing to request permission\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rijksmuseum/eligibility/rijksmuseum-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Rijksmuseum's own page on 2026-11-10.
synthetic: false
tags:
- Museums
- Cultural Heritage
- Open Data
- Linked Data
- OAI-PMH
- IIIF
- Dutch Heritage
- Public APIs
- Art
---
