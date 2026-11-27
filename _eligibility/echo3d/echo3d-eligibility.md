---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a business or some other entity, you state that you are authorized to grant all licenses set forth in these Terms
    type: business
  - text: you are not under the age of 13 (as no one under 13 is allowed to create an account or use the Service)
    type: individual
  minimum_age:
    text: you are not under the age of 13
    value: '13'
  restricted_uses:
  - summary: Competitors barred
    text: You will not access the Services if you are a competitor of echo3D or otherwise unauthorized to access the Services.
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
name: echo3D
provenance_date: '2026-11-09'
provider_name: echo3D
provider_slug: echo3d
slug: echo3d-eligibility
source_date: '2026-11-09'
source_filename: echo3d-eligibility.yml
source_heading: Eligibility
source_page: https://www.echo3d.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: echo3D\naid: echo3d\nurl: https://www.echo3d.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a business or some other entity, you state that you are authorized\n    to grant all licenses set forth in these Terms\n- type: individual\n  text: you are not under the age of 13 (as no one under 13 is allowed to create an account or use the Service)\nrestricted_uses:\n- summary: Competitors barred\n  text: You will not access the Services if you are a competitor of echo3D or otherwise unauthorized\
  \ to access the\n    Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are not under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/echo3d/eligibility/echo3d-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from echo3D's own page on 2026-11-09.
synthetic: false
tags:
- Company
- 3D
- Augmented Reality
- Virtual Reality
- Digital Asset Management
- 3D Models
- Content Delivery
- Developer Tools
- SDK
- WebAR
---
