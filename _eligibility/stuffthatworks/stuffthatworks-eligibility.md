---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may use the Service for your personal use subject to these Terms
    type: individual
  minimum_age:
    text: Children under the age of 16 are prohibited from creating an account and becoming a member of Stuff That Works.
    value: '16'
  restricted_uses:
  - summary: Commercial use prohibited
    text: make commercial use of the Service or related content
  - summary: Minimum age of 16
    text: Children under the age of 16 are prohibited from creating an account and becoming a member of Stuff That Works.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to refuse to allow a user to open or maintain a member account, even if such user was already a registered member, and/or to delete a member account, for any reason at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StuffThatWorks
provenance_date: '2026-11-10'
provider_name: StuffThatWorks
provider_slug: stuffthatworks
slug: stuffthatworks-eligibility
source_date: '2026-11-10'
source_filename: stuffthatworks-eligibility.yml
source_heading: Eligibility
source_page: https://www.stuffthatworks.health/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StuffThatWorks\naid: stuffthatworks\nurl: https://www.stuffthatworks.health/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may use the Service for your personal use subject to these Terms\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: make commercial use of the Service or related content\n- summary: Minimum age of 16\n  text: Children under the age of 16 are prohibited from creating an account and becoming a member of Stuff That\n    Works.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: We reserve the right to refuse to allow a user to open or maintain a member account, even if such user was\n    already a registered member, and/or to delete a member account, for any reason at our sole discretion.\nminimum_age:\n  value: '16'\n  text: Children under the age of 16 are prohibited from creating an account and becoming a member of Stuff That\n    Works.\n"
source_yaml_url: https://artifacts.apis.io/stuffthatworks/eligibility/stuffthatworks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from StuffThatWorks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Patient Community
- Chronic Conditions
- Crowdsourcing
- Medical Research
- Collective Intelligence
---
