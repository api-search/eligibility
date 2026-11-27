---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your lawful, non-commercial, personal career development purposes
    type: individual
  minimum_age:
    text: The Services are not intended for use by individuals under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Legal, medical, or financial advice
    text: Use the Services for legal, medical, or financial advice
  - summary: Disinformation, impersonation, deepfakes
    text: Use the Services (i) to create or spread disinformation or misleading content; (ii) to identify real individuals or impersonate individuals, organizations, or brands; or (iii) creating deepfakes, synthetic media, or other deceptive AI-generated materials
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
name: Blomma
provenance_date: '2026-11-09'
provider_name: Blomma
provider_slug: blomma
slug: blomma-eligibility
source_date: '2026-11-09'
source_filename: blomma-eligibility.yml
source_heading: Eligibility
source_page: https://www.blomma.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blomma\naid: blomma\nurl: https://www.blomma.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your lawful, non-commercial, personal career development purposes\nrestricted_uses:\n- summary: Legal, medical, or financial advice\n  text: Use the Services for legal, medical, or financial advice\n- summary: Disinformation, impersonation, deepfakes\n  text: Use the Services (i) to create or spread disinformation or misleading content; (ii) to identify real individuals\n    or impersonate individuals, organizations,\
  \ or brands; or (iii) creating deepfakes, synthetic media, or other\n    deceptive AI-generated materials\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for use by individuals under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/blomma/eligibility/blomma-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blomma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Career Coaching
- Artificial Intelligence
- Coaching
- Professional Development
- Emotional Intelligence
- Productivity
- Consumer Applications
- Human Resources
---
