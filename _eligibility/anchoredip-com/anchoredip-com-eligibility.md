---
api_specs:
- filename: anchoredip-com-openapi-generated.yml
  format: yaml
  label: AnchoredIP API
  slug: anchoredip-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchoredip-com/openapi/_ae-authored/anchoredip-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available to businesses and individuals who provide accurate identification and contact information.
    type: individual
  - text: The Service is available to businesses and individuals who provide accurate identification and contact information.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right to decline service at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AnchoredIP
provenance_date: '2026-11-09'
provider_name: AnchoredIP
provider_slug: anchoredip-com
slug: anchoredip-com-eligibility
source_date: '2026-11-09'
source_filename: anchoredip-com-eligibility.yml
source_heading: Eligibility
source_page: https://anchoredip.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnchoredIP\naid: anchoredip-com\nurl: https://anchoredip.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available to businesses and individuals who provide accurate identification and contact information.\n- type: business\n  text: The Service is available to businesses and individuals who provide accurate identification and contact information.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: We reserve the right to decline service at our discretion.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anchoredip-com/eligibility/anchoredip-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from AnchoredIP's own page on 2026-11-09.
synthetic: false
tags:
- StaticIP
- Networking
- Cloud
- WireGuard
- Outbound
---
