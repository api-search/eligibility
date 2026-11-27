---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The availability of the Trial depends on the geographic location inferred from the User’s IP address.
  entity_types:
  - text: 'Client: means the person or company that has created a User Account on the Rayon Platform'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Student tier non-commercial only
    text: Use of the Student tier is strictly limited to educational, academic, or personal learning purposes and shall not be used for any commercial, professional, or revenue-generating activity.
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
name: Rayon
provenance_date: '2026-11-10'
provider_name: Rayon
provider_slug: rayon
slug: rayon-eligibility
source_date: '2026-11-10'
source_filename: rayon-eligibility.yml
source_heading: Eligibility
source_page: https://www.rayon.design/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rayon\naid: rayon\nurl: https://www.rayon.design/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The availability of the Trial depends on the geographic location inferred from the User’s IP address.\nentity_types:\n- type: business\n  text: 'Client: means the person or company that has created a User Account on the Rayon Platform'\nrestricted_uses:\n- summary: Student tier non-commercial only\n  text: Use of the Student tier is strictly limited to educational, academic, or personal learning purposes and\n    shall not be used for any commercial, professional, or\
  \ revenue-generating activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rayon/eligibility/rayon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Rayon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Artificial Intelligence
- CAD
- Architecture
- Design
- BIM
- Interior Design
- Collaboration
---
