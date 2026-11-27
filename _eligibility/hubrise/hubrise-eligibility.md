---
api_specs:
- filename: hubrise-openapi-generated.yml
  format: yaml
  label: HubRise API
  slug: hubrise-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hubrise/openapi/_ae-authored/hubrise-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual or legal entity, whether acting in a private or professional capacity, and whether governed by private or public law, wishing to access or use one or more of the services offered by HubRise
    type: individual
  - text: If the User is acting on behalf of an entity, they declare and affirm that they have the authority to bind said entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: Any use of the Services for illegal purposes.
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
name: HubRise
provenance_date: '2026-11-09'
provider_name: HubRise
provider_slug: hubrise
slug: hubrise-eligibility
source_date: '2026-11-09'
source_filename: hubrise-eligibility.yml
source_heading: Eligibility
source_page: https://www.hubrise.com/legal/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HubRise\naid: hubrise\nurl: https://www.hubrise.com/legal/general-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual or legal entity, whether acting in a private or professional capacity, and whether governed\n    by private or public law, wishing to access or use one or more of the services offered by HubRise\n- type: business\n  text: If the User is acting on behalf of an entity, they declare and affirm that they have the authority to bind\n    said entity.\nrestricted_uses:\n- summary: Illegal purposes\n\
  \  text: Any use of the Services for illegal purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hubrise/eligibility/hubrise-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from HubRise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- Retail
- Hospitality
---
