---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Students must be at least 18 years old to use the Cambly Site. Students under the age of 18 may use the Cambly Kids Site, but only if their parent or legal guardian has provided Cambly verifiable consent and agreed to this Agreement.
    type: individual
  - text: If you are a Tutor or prospective Tutor, you represent that you are over the age of 18.
    type: individual
  minimum_age:
    text: Students must be at least 18 years old to use the Cambly Site.
    value: '18'
  restricted_uses:
  - summary: Use inconsistent with intended purpose or unlawful
    text: access or use the Platform for any purpose that is inconsistent with its intended purpose, or for any purpose that is unlawful or prohibited by this Agreement
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
name: Cambly
provenance_date: '2026-11-09'
provider_name: Cambly
provider_slug: cambly
slug: cambly-eligibility
source_date: '2026-11-09'
source_filename: cambly-eligibility.yml
source_heading: Eligibility
source_page: https://www.cambly.com/legal/user_agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cambly\naid: cambly\nurl: https://www.cambly.com/legal/user_agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Students must be at least 18 years old to use the Cambly Site. Students under the age of 18 may use the\n    Cambly Kids Site, but only if their parent or legal guardian has provided Cambly verifiable consent and agreed\n    to this Agreement.\n- type: individual\n  text: If you are a Tutor or prospective Tutor, you represent that you are over the age of 18.\nrestricted_uses:\n- summary: Use inconsistent with intended\
  \ purpose or unlawful\n  text: access or use the Platform for any purpose that is inconsistent with its intended purpose, or for any purpose\n    that is unlawful or prohibited by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Students must be at least 18 years old to use the Cambly Site.\n"
source_yaml_url: https://artifacts.apis.io/cambly/eligibility/cambly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cambly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- Language Learning
- EdTech
- Tutoring
- Video
- Marketplace
---
