---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are acting on behalf of a company or entity that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, non-transferable access
    text: Your right to access and use the Sites and the Services is personal to you and is not transferable by you to any other person or entity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PayIt
provenance_date: '2026-11-10'
provider_name: PayIt
provider_slug: payit
slug: payit-eligibility
source_date: '2026-11-10'
source_filename: payit-eligibility.yml
source_heading: Eligibility
source_page: https://payitgov.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayIt\naid: payit\nurl: https://payitgov.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are acting on behalf of a company or entity that you have the authority to bind such entity\nrestricted_uses:\n- summary: Personal, non-transferable access\n  text: Your right to access and use the Sites and the Services is personal to you and is not transferable by you\n    to any other person or entity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may verify your identity.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payit/eligibility/payit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from PayIt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Government
- GovTech
- Payments
- Digital Government
- Public Sector
- Citizen Experience
- DMV
---
