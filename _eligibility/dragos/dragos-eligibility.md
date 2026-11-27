---
api_specs:
- filename: dragos-indicators-api-openapi.yml
  format: yaml
  label: Dragos Indicators API
  slug: dragos-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-indicators-api-openapi.yml
- filename: dragos-products-api-openapi.yml
  format: yaml
  label: Dragos Products API
  slug: dragos-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-products-api-openapi.yml
- filename: dragos-tags-api-openapi.yml
  format: yaml
  label: Dragos Tags API
  slug: dragos-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dragos/openapi/dragos-tags-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use our Sites.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use our Sites.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Except as authorized by law, you agree and warrant not to export or re-export the Software or Technical Data to any county, or to any person, entity, or end-user subject to U.S. export controls
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
name: Dragos
provenance_date: '2026-11-09'
provider_name: Dragos
provider_slug: dragos
slug: dragos-eligibility
source_date: '2026-11-09'
source_filename: dragos-eligibility.yml
source_heading: Eligibility
source_page: https://www.dragos.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dragos\naid: dragos\nurl: https://www.dragos.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Sites.\nrestricted_uses:\n- summary: Export restrictions\n  text: Except as authorized by law, you agree and warrant not to export or re-export the Software or Technical\n    Data to any county, or to any person, entity, or end-user subject to U.S. export controls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years of age to use our Sites.\n"
source_yaml_url: https://artifacts.apis.io/dragos/eligibility/dragos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dragos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- OT Security
- ICS
- Threat Intelligence
- Industrial Control Systems
- Indicators of Compromise
- STIX
- Vulnerability Management
- Security
---
