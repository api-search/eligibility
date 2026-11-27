---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are using the Platform on behalf of another party (for example: a company or an organisation), you represent and warrant that you have the authority to enter into these Terms on behalf of such party'
    type: business
  - text: The Platform is not intended for individuals under the age of eighteen (18)
    type: individual
  minimum_age:
    text: By accessing the Platform, you represent that you are at least eighteen (18) years old or the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Educational version limited to education
    text: you shall use and access the Platform solely for educational purposes
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
name: Snaptrude
provenance_date: '2026-11-10'
provider_name: Snaptrude
provider_slug: snaptrude
slug: snaptrude-eligibility
source_date: '2026-11-10'
source_filename: snaptrude-eligibility.yml
source_heading: Eligibility
source_page: https://www.snaptrude.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snaptrude\naid: snaptrude\nurl: https://www.snaptrude.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are using the Platform on behalf of another party (for example: a company or an organisation), you\n    represent and warrant that you have the authority to enter into these Terms on behalf of such party'\n- type: individual\n  text: The Platform is not intended for individuals under the age of eighteen (18)\nrestricted_uses:\n- summary: Educational version limited to education\n  text: you shall use and access the\
  \ Platform solely for educational purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing the Platform, you represent that you are at least eighteen (18) years old or the age of majority\n    in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/snaptrude/eligibility/snaptrude-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Snaptrude's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design
- Architecture
- BIM
- 3D Modeling
- AEC
- Plugins
- Developer Tools
- Software-as-a-Service
---
