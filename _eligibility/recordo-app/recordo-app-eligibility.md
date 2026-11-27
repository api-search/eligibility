---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years of age to create an account or otherwise use the Service.
    type: individual
  minimum_age:
    text: You must be at least 16 years of age to create an account or otherwise use the Service.
    value: '16'
  restricted_uses:
  - summary: No medical or therapeutic use
    text: Do not use Recordo as a replacement for medical, psychiatric, psychological, or therapeutic care.
  - summary: No decisions about others' medical, legal, safety matters
    text: Use the Service to make decisions about another person's medical, psychological, financial, legal, or safety situation;
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
name: recordo-app
provenance_date: '2026-11-10'
provider_name: recordo-app
provider_slug: recordo-app
slug: recordo-app-eligibility
source_date: '2026-11-10'
source_filename: recordo-app-eligibility.yml
source_heading: Eligibility
source_page: https://recordo.app/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: recordo-app\naid: recordo-app\nurl: https://recordo.app/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to create an account or otherwise use the Service.\nrestricted_uses:\n- summary: No medical or therapeutic use\n  text: Do not use Recordo as a replacement for medical, psychiatric, psychological, or therapeutic care.\n- summary: No decisions about others' medical, legal, safety matters\n  text: Use the Service to make decisions about another person's medical, psychological, financial,\
  \ legal, or safety\n    situation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to create an account or otherwise use the Service.\n"
source_yaml_url: https://artifacts.apis.io/recordo-app/eligibility/recordo-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from recordo-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Productivity
- ADHD
- Mental Health
---
