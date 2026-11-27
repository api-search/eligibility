---
api_specs:
- filename: university-of-cape-town-catalog-api-openapi.yml
  format: yaml
  label: DataFirst Microdata Catalog API (NADA)
  slug: datafirst-nada
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-cape-town/openapi/university-of-cape-town-catalog-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These users must be acting on behalf of an organization, who must take responsibility for the use.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Enclave access
    text: Users interested in accessing these datasets will be asked to complete an application form demonstrating a legitimate need to access these data to fulfill a stated statistical or research purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: who have received authorization to access them after submitting a documented application and signing an agreement governing the data's use.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: University of Cape Town
provenance_date: '2026-11-10'
provider_name: University of Cape Town
provider_slug: university-of-cape-town
slug: university-of-cape-town-eligibility
source_date: '2026-11-10'
source_filename: university-of-cape-town-eligibility.yml
source_heading: Eligibility
source_page: https://www.datafirst.uct.ac.za/dataportal/index.php/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of Cape Town\naid: university-of-cape-town\nurl: https://www.datafirst.uct.ac.za/dataportal/index.php/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: These users must be acting on behalf of an organization, who must take responsibility for the use.\nrestricted_uses:\n- summary: Enclave access\n  text: Users interested in accessing these datasets will be asked to complete an application form demonstrating\n    a legitimate need to access these data to fulfill a stated statistical or research purpose.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: who have received authorization to access them after submitting a documented application and signing an\n    agreement governing the data's use.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/university-of-cape-town/eligibility/university-of-cape-town-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from University of Cape Town's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Public Research University
- South Africa
- Africa
- Research Data
- Open Data
- Institutional Repository
- OAI-PMH
- Identity Federation
- Microdata
- Research Computing
---
