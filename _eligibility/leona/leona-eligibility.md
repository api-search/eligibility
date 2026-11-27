---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either a natural person and/or through a legal person with whom you manage your professional activity
    type: individual
  - text: through a legal person with whom you manage your professional activity
    type: business
  minimum_age:
    text: you, as a User, must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Only for the Site's stated purpose
    text: Any use other than the purpose of the Site and/or the Applications is expressly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: LEONA has no obligation to verify the identity of the Users
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Leona
provenance_date: '2026-11-09'
provider_name: Leona
provider_slug: leona
slug: leona-eligibility
source_date: '2026-11-09'
source_filename: leona-eligibility.yml
source_heading: Eligibility
source_page: https://www.leona.health/en/tyc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leona\naid: leona\nurl: https://www.leona.health/en/tyc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either a natural person and/or through a legal person with whom you manage your professional activity\n- type: business\n  text: through a legal person with whom you manage your professional activity\nrestricted_uses:\n- summary: Only for the Site's stated purpose\n  text: Any use other than the purpose of the Site and/or the Applications is expressly prohibited.\nverification:\n  kyc: false\n  kyb: null\n  approval_required:\
  \ null\n  text: LEONA has no obligation to verify the identity of the Users\nminimum_age:\n  value: '18'\n  text: you, as a User, must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/leona/eligibility/leona-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Leona's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Messaging
- WhatsApp
- Artificial Intelligence
- Patient Communication
- Latin America
- Mobile
---
