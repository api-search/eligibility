---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting this Agreement does so on behalf of an entity, that individual represents that he or she has authority to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: You must be at least 18 years old and the owner or authorized user of the mobile number you enroll.
    value: '18'
  restricted_uses:
  - summary: No pressuring messaging enrollment
    text: Customer shall not require, direct, or pressure any individual to enroll in or remain enrolled in a Messaging Program
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
name: Rilla
provenance_date: '2026-11-10'
provider_name: Rilla
provider_slug: rilla
slug: rilla-eligibility
source_date: '2026-11-10'
source_filename: rilla-eligibility.yml
source_heading: Eligibility
source_page: https://www.rilla.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rilla\naid: rilla\nurl: https://www.rilla.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement does so on behalf of an entity, that individual represents that\n    he or she has authority to bind that entity to this Agreement.\nrestricted_uses:\n- summary: No pressuring messaging enrollment\n  text: Customer shall not require, direct, or pressure any individual to enroll in or remain enrolled in a Messaging\n    Program\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and the owner or authorized user of the mobile number you enroll.\n"
source_yaml_url: https://artifacts.apis.io/rilla/eligibility/rilla-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rilla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Conversation Intelligence
- Sales
- Coaching
- Sales Enablement
- Speech Analytics
- Machine Learning
---
