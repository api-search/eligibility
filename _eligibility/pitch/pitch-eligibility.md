---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Free services offered by Pitch address both consumers ( Verbraucher ) pursuant to Section 13 German Civil Code
    type: individual
  - text: Paid Plans (as defined in Section 3.2) are offered exclusively to companies or persons that legally qualify as entrepreneurs ( Unternehmer )
    type: business
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
name: Pitch
provenance_date: '2026-11-10'
provider_name: Pitch
provider_slug: pitch
slug: pitch-eligibility
source_date: '2026-11-10'
source_filename: pitch-eligibility.yml
source_heading: Eligibility
source_page: https://pitch.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pitch\naid: pitch\nurl: https://pitch.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Free services offered by Pitch address both consumers ( Verbraucher ) pursuant to Section 13 German Civil\n    Code\n- type: business\n  text: Paid Plans (as defined in Section 3.2) are offered exclusively to companies or persons that legally qualify\n    as entrepreneurs ( Unternehmer )\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pitch/eligibility/pitch-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Pitch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Presentations
- Productivity
- Collaboration
- Software-as-a-Service
---
