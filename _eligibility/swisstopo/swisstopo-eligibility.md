---
api_specs:
- filename: swisstopo-layers-api-openapi.yml
  format: yaml
  label: swisstopo Layers API
  slug: swisstopo-layers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisstopo/openapi/swisstopo-layers-api-openapi.yml
- filename: swisstopo-vocabularies-api-openapi.yml
  format: yaml
  label: swisstopo Vocabularies API
  slug: swisstopo-vocabularies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisstopo/openapi/swisstopo-vocabularies-api-openapi.yml
- filename: swisstopo-wms-api-openapi.yml
  format: yaml
  label: swisstopo WMS API
  slug: swisstopo-wms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisstopo/openapi/swisstopo-wms-api-openapi.yml
- filename: swisstopo-wmts-api-openapi.yml
  format: yaml
  label: swisstopo WMTS API
  slug: swisstopo-wmts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/swisstopo/openapi/swisstopo-wmts-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: tax-exempt non-profit organisations can obtain paper maps at a reduced price, provided that they use them for teaching map-reading or for internal use or research purposes only.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Reduced-price maps limited to teaching or internal research
    text: provided that they use them for teaching map-reading or for internal use or research purposes only.
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
name: swisstopo
provenance_date: '2026-11-10'
provider_name: swisstopo
provider_slug: swisstopo
slug: swisstopo-eligibility
source_date: '2026-11-10'
source_filename: swisstopo-eligibility.yml
source_heading: Eligibility
source_page: https://www.swisstopo.admin.ch/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: swisstopo\naid: swisstopo\nurl: https://www.swisstopo.admin.ch/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: tax-exempt non-profit organisations can obtain paper maps at a reduced price, provided that they use them\n    for teaching map-reading or for internal use or research purposes only.\nrestricted_uses:\n- summary: Reduced-price maps limited to teaching or internal research\n  text: provided that they use them for teaching map-reading or for internal use or research purposes only.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/swisstopo/eligibility/swisstopo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from swisstopo's own page on 2026-11-10.
synthetic: false
tags:
- Geodata
- Government
- Switzerland
- Mapping
- Open Data
---
