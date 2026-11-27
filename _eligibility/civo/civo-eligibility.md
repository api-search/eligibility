---
api_specs:
- filename: civo-openapi-generated.yml
  format: yaml
  label: Civo API
  slug: civo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civo/openapi/_ae-authored/civo-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You as an individual or the organisation, company, or other entity that you have the legal authority to bind to this Agreement
    type: individual
  - text: the organisation, company, or other entity that you have the legal authority to bind to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk use excluded
    text: No rights are granted to You to use the software services in any application or situation where failure of the software services could lead to death or serious injury of any person, or to severe physical or environmental damage
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
name: Civo
provenance_date: '2026-11-09'
provider_name: Civo
provider_slug: civo
slug: civo-eligibility
source_date: '2026-11-09'
source_filename: civo-eligibility.yml
source_heading: Eligibility
source_page: https://www.civo.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Civo\naid: civo\nurl: https://www.civo.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You as an individual or the organisation, company, or other entity that you have the legal authority to\n    bind to this Agreement\n- type: business\n  text: the organisation, company, or other entity that you have the legal authority to bind to this Agreement\nrestricted_uses:\n- summary: High-risk use excluded\n  text: No rights are granted to You to use the software services in any application or situation where failure\n    of\
  \ the software services could lead to death or serious injury of any person, or to severe physical or environmental\n    damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/civo/eligibility/civo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Civo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Kubernetes
- Cloud Computing
- Infrastructure
- Artificial Intelligence
- GPU
- Sovereign Cloud
---
