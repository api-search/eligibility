---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'each party represents and warrants to the other party that: it is a duly organized, validly existing, and in good standing as a corporation or other entity'
    type: business
  - text: If Customer (or any of its customers) is an agency, department, or other entity of any government
    type: government
  minimum_age:
    text: null
    value: null
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
name: Pragma
provenance_date: '2026-11-10'
provider_name: Pragma
provider_slug: pragma
slug: pragma-eligibility
source_date: '2026-11-10'
source_filename: pragma-eligibility.yml
source_heading: Eligibility
source_page: https://pragma.gg/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pragma\naid: pragma\nurl: https://pragma.gg/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'each party represents and warrants to the other party that: it is a duly organized, validly existing, and\n    in good standing as a corporation or other entity'\n- type: government\n  text: If Customer (or any of its customers) is an agency, department, or other entity of any government\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/pragma/eligibility/pragma-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Pragma's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Gaming
- Game Backend
- Live Operations
- Player Accounts
- Authentication
- Commerce
- Playtesting
- Community
- Analytics
- Developer Tools
---
