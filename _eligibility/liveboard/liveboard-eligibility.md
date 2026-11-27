---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Schools, educators, tutors, teachers, instructors, and students can benefit from the Services we provide.
    type: other
  minimum_age:
    text: Users under 13 have to be invited to use the Services by the teacher, tutor or school who has registered an account with us.
    value: '13'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: You must use our Services only for lawful purposes, you have no right to register or access our services for unlawful purposes or use those services to commit fraud.
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
name: Liveboard
provenance_date: '2026-11-09'
provider_name: Liveboard
provider_slug: liveboard
slug: liveboard-eligibility
source_date: '2026-11-09'
source_filename: liveboard-eligibility.yml
source_heading: Eligibility
source_page: https://www.liveboard.online/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liveboard\naid: liveboard\nurl: https://www.liveboard.online/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Schools, educators, tutors, teachers, instructors, and students can benefit from the Services we provide.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: You must use our Services only for lawful purposes, you have no right to register or access our services\n    for unlawful purposes or use those services to commit fraud.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: Users under 13 have to be invited to use the Services by the teacher, tutor or school who has registered\n    an account with us.\n"
source_yaml_url: https://artifacts.apis.io/liveboard/eligibility/liveboard-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Liveboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Tutoring
- Virtual Classroom
- Online Whiteboard
- Scheduling
- Billing
- Software-as-a-Service
---
