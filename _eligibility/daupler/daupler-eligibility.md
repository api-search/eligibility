---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are using Services on behalf of a company or organization, such company or organization will also be considered a party to this Agreement and "User".
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Only agreed purposes
    text: User shall not use the Services for purposes other than as set forth in the Agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Each User will have unique access codes to be used to access the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Daupler
provenance_date: '2026-11-09'
provider_name: Daupler
provider_slug: daupler
slug: daupler-eligibility
source_date: '2026-11-09'
source_filename: daupler-eligibility.yml
source_heading: Eligibility
source_page: https://daupler.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daupler\naid: daupler\nurl: https://daupler.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are using Services on behalf of a company or organization, such company or organization will also\n    be considered a party to this Agreement and \"User\".\nrestricted_uses:\n- summary: Only agreed purposes\n  text: User shall not use the Services for purposes other than as set forth in the Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Each User will have unique access codes\
  \ to be used to access the Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/daupler/eligibility/daupler-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Daupler's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Response Management
- Utilities
- Public Works
- Emergency Response
- Dispatch
- Notification
- Water
- Software-as-a-Service
---
