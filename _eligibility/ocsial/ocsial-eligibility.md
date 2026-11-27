---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, as user, whether personally or on behalf of an entity
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of content
    text: You must not use any part of the content on our Website for commercial purposes without obtaining a license to do so from us or our licensors.
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
name: OCSiAl
provenance_date: '2026-11-10'
provider_name: OCSiAl
provider_slug: ocsial
slug: ocsial-eligibility
source_date: '2026-11-10'
source_filename: ocsial-eligibility.yml
source_heading: Eligibility
source_page: https://ocsial.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OCSiAl\naid: ocsial\nurl: https://ocsial.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, as user, whether personally or on behalf of an entity\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Commercial use of content\n  text: You must not use any part of the content on our Website for commercial purposes without obtaining a license\n    to do so from us or our licensors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ocsial/eligibility/ocsial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from OCSiAl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advanced Materials
- Nanotechnology
- Carbon Nanotubes
- Chemicals
- Manufacturing
- Batteries
- Coatings
- Luxembourg
---
