---
api_specs:
- filename: useanything-openapi-generated.yml
  format: yaml
  label: Useanything API
  slug: useanything-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/useanything/openapi/_ae-authored/useanything-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represents and warrants that You are (a) not located in, organized under the laws of, or ordinarily resident in any country or territory subject to territorial sanctions
  entity_types:
  - text: If the person downloading or using the Software or Services is an employee, agent or contractor of a corporate entity and using the Software or Services within the scope of their employment, agency or primarily for the benefit of the corporate entity, the Terms are between the corporate entity and Mintplex Labs
    type: business
  - text: the person or entity that downloads or uses the Software and uses the Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You also understand that the Software is not designed to be used for any illegal or unauthorized purposes.
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
name: Useanything
provenance_date: '2026-11-10'
provider_name: Useanything
provider_slug: useanything
slug: useanything-eligibility
source_date: '2026-11-10'
source_filename: useanything-eligibility.yml
source_heading: Eligibility
source_page: https://docs.useanything.com/mobile/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Useanything\naid: useanything\nurl: https://docs.useanything.com/mobile/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represents and warrants that You are (a) not located in, organized under the laws of, or ordinarily\n    resident in any country or territory subject to territorial sanctions\nentity_types:\n- type: business\n  text: If the person downloading or using the Software or Services is an employee, agent or contractor of a corporate\n    entity and using the Software or Services within the scope of their employment, agency or primarily for the\n    benefit of\
  \ the corporate entity, the Terms are between the corporate entity and Mintplex Labs\n- type: individual\n  text: the person or entity that downloads or uses the Software and uses the Services\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You also understand that the Software is not designed to be used for any illegal or unauthorized purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/useanything/eligibility/useanything-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Useanything's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Placeholder
- API-Evangelist
---
