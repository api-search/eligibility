---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is designed for business or professional use only.
    type: business
  minimum_age:
    text: The Service may not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: No personal, family or household use
    text: may not use the Service for personal, family, or household purposes
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
name: Tone
provenance_date: '2026-11-10'
provider_name: Tone
provider_slug: tone
slug: tone-eligibility
source_date: '2026-11-10'
source_filename: tone-eligibility.yml
source_heading: Eligibility
source_page: https://tone.is/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tone\naid: tone\nurl: https://tone.is/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is designed for business or professional use only.\nrestricted_uses:\n- summary: No personal, family or household use\n  text: may not use the Service for personal, family, or household purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service may not be used by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/tone/eligibility/tone-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tone's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payouts
- Royalties
- Royalty Management
- Music
- Music Rights
- Fintech
- Software-as-a-Service
---
