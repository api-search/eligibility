---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to enter into this Agreement personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: Time-critical or mission-critical functions
    text: will not be used, and are not licensed for use, in connection with any of your time-critical or mission-critical functions
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
name: Vectary
provenance_date: '2026-11-10'
provider_name: Vectary
provider_slug: vectary
slug: vectary-eligibility
source_date: '2026-11-10'
source_filename: vectary-eligibility.yml
source_heading: Eligibility
source_page: https://www.vectary.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vectary\naid: vectary\nurl: https://www.vectary.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to enter into this Agreement personally or on behalf of the entity you have named\n    as the user\nrestricted_uses:\n- summary: Time-critical or mission-critical functions\n  text: will not be used, and are not licensed for use, in connection with any of your time-critical or mission-critical\n    functions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are (i) at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/vectary/eligibility/vectary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vectary's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design Tech
- 3D Design
- Augmented Reality
- 3D Configurator
- Product Visualization
- E-Commerce
---
